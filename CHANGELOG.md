# Changelog

## 1.0.0 (2023-06-05)


### Features

* added buffer-local keymaps ([18635d8](https://github.com/folke/edgy.nvim/commit/18635d8854b02b0d263aa758516f58e7052dd468))
* added close methods ([e4ca3ab](https://github.com/folke/edgy.nvim/commit/e4ca3ab70275472b685ddaa91fd627fb44e01750))
* added pinned views ([07a1b6d](https://github.com/folke/edgy.nvim/commit/07a1b6d7b7d5ca0cd215426eca8558b6a535758c))
* added sidebar as a prop of view ([4883d03](https://github.com/folke/edgy.nvim/commit/4883d0356e0d6d25f74a51951cf8853f0caec56e))
* added small util module ([30a13af](https://github.com/folke/edgy.nvim/commit/30a13afa34bfdda1346365adfd4dca1cc4b09da3))
* added support for floating windows ([8fb1105](https://github.com/folke/edgy.nvim/commit/8fb1105a6987eeb0984d6b89556e0a14a83adf8f))
* animations ([b4707ad](https://github.com/folke/edgy.nvim/commit/b4707ad4dc3326aabb313b624d0f2ff6b247ca07))
* better handling of main windows ([ec85a1f](https://github.com/folke/edgy.nvim/commit/ec85a1f8435c4f0dff5419884f5a1cd088eba303))
* collapsing vertical views collpse to window title ([8b9b76d](https://github.com/folke/edgy.nvim/commit/8b9b76dc1a96f0c9a04a0091e2b2017aab698085))
* **config:** made all hl groups and view options configurable ([f0a6ab3](https://github.com/folke/edgy.nvim/commit/f0a6ab36f8dcb076aae0b52ac1021fab2c5608d3))
* expand view when needed when buffer becomes the current ([30b90de](https://github.com/folke/edgy.nvim/commit/30b90de37efde0a5ac2e95bdde837cdbfea59d76))
* initial commit 🎉 ([8ccc3b0](https://github.com/folke/edgy.nvim/commit/8ccc3b02f1d957917592a66146301fcd080ad3fe))
* **layout:** added some debugging tools ([f7bfbb4](https://github.com/folke/edgy.nvim/commit/f7bfbb4ee5f8567e781a539ab0a0e13781eb080d))
* retry layout when needed ([2e7f2c0](https://github.com/folke/edgy.nvim/commit/2e7f2c01f68b68cf69d27bd66f2e120081a1e7c8))
* **sidebar:** added sidebar:close() ([94de9c6](https://github.com/folke/edgy.nvim/commit/94de9c66631618e65bcb9a772f7079b7a5ab1fa9))
* simplified config ([f48b78e](https://github.com/folke/edgy.nvim/commit/f48b78e52de788f97f7fdba57098a3ed2a0ef53d))
* use ctrl-q to hide a window in the sidebar ([5974a31](https://github.com/folke/edgy.nvim/commit/5974a312166c352acbc6398d038bf924510d65fa))
* **util:** added debounce ([c0ae068](https://github.com/folke/edgy.nvim/commit/c0ae06840139c656b0f83ef4d990226629ad5a0d))
* **util:** added with_retry and noautocmd ([c9e5236](https://github.com/folke/edgy.nvim/commit/c9e523669850a02c548ea8b6e39042ec06c85b39))
* **view:** added optional filtering of view windows ([7199063](https://github.com/folke/edgy.nvim/commit/719906302c5378857eba333bb20a71b30377bdbf))


### Bug Fixes

* disable splitkeep when needed in nvim_win_set_height ([530f982](https://github.com/folke/edgy.nvim/commit/530f98219560c29994bdff2f213222c75c9a5400))
* **hacks:** check that win is valid ([aef29eb](https://github.com/folke/edgy.nvim/commit/aef29eb6164e3f6a644cdd7194fb0218a5ccaf12))
* **hacks:** disable splitkeep for now when resizing. See upstream PR ([eef534c](https://github.com/folke/edgy.nvim/commit/eef534ccdf5663eead994c7d46dc3259cbd74cb3))
* **layout:** also check that sidebar window sizes are equal in needs_layout ([1b09518](https://github.com/folke/edgy.nvim/commit/1b09518d8a7d52ff03882b7a3c3b12b51c33ad92))
* **layout:** fixed calculation of long edge ([0fc9c80](https://github.com/folke/edgy.nvim/commit/0fc9c80f1729f6ddb93af449f47715ad7d3471ee))
* **layout:** improved viewstate handling ([6448c8d](https://github.com/folke/edgy.nvim/commit/6448c8de3a7b04e0e94322bb550a574d5ea9a892))
* **layout:** update layout on WinNew and WinResized as well ([40077a7](https://github.com/folke/edgy.nvim/commit/40077a7cec0600e98f4a077b4c5a3d66886653e2))
* **layout:** use debounce for resizes ([640b98b](https://github.com/folke/edgy.nvim/commit/640b98b35483a0aac014df1c1c154089384848c4))
* **layout:** weird one-off bug on horizontal sidebars ([875853a](https://github.com/folke/edgy.nvim/commit/875853a24e448e5109faa64daecab2c84080d0e8))
* make sure to have at least one window open ([6ae8d23](https://github.com/folke/edgy.nvim/commit/6ae8d23e3e5f567d2d0bd6eb7378e5851a2186de))
* move state save/restore to updater ([6c482c1](https://github.com/folke/edgy.nvim/commit/6c482c142bdd3dffc2e457f707cb34b71905539b))
* no longer seems needed to change splitkeep ([62d1132](https://github.com/folke/edgy.nvim/commit/62d11321aaa649d5cfea2f52339afc3c39aa0b80))
* no need to store last window ([2d080f8](https://github.com/folke/edgy.nvim/commit/2d080f808c6e262387869e9eccc013b605d72344))
* only check for windows on the current tabpage ([794ab42](https://github.com/folke/edgy.nvim/commit/794ab423120dcbe14f63c3826e1af886c2b47782))
* properly deal with winheight=1 and winbar ([fb30fcc](https://github.com/folke/edgy.nvim/commit/fb30fcc7c4159514143d6435fc25719ff017412f))
* set winfixwidth to prevent windows.nvim and other plugins to change the width ([933b235](https://github.com/folke/edgy.nvim/commit/933b235eccaac43c18938a464705dd8dec31c5eb))
* **sidebar:** resize when no window is open ([83621f5](https://github.com/folke/edgy.nvim/commit/83621f5817b023e70d585ccabb5c105b6922b6bc))
* **sidebar:** use Util.noautocmd for sidebar.close ([0eb178d](https://github.com/folke/edgy.nvim/commit/0eb178df7150d51ac9c64d6b529b688b1dbbf82e))
* when collapsing a window, jump to a non sidebar window ([156d69e](https://github.com/folke/edgy.nvim/commit/156d69e16077a7f92b87addb2c455bde2873ebaf))
* **window:** better handling of window hiding ([6f093eb](https://github.com/folke/edgy.nvim/commit/6f093eba91ce42edfc2b9dfa7422a7d2b495ffa3))
* **window:** dont try opening a pinned window more than once ([3cc5be8](https://github.com/folke/edgy.nvim/commit/3cc5be87751e72b51db8c5825c4712d7800e857a))
* **window:** go to main should skip floating windows ([993b576](https://github.com/folke/edgy.nvim/commit/993b576cf44dcfe92e4d2ffc85515abf427c33c1))
* **window:** resize sidebar only when open/close windows ([a35bab7](https://github.com/folke/edgy.nvim/commit/a35bab74b9f3aaab5aaacc2c20497bc4512c190f))
* winsaveview and winresetview ([82fcdca](https://github.com/folke/edgy.nvim/commit/82fcdca453793b33d197ecbd766f52c0ea7a25eb))


### Performance Improvements

* only resize when sidebar has windows ([fc7b6da](https://github.com/folke/edgy.nvim/commit/fc7b6daf8f2ec18c12b916c5639b917b45c6c325))
* reduced a lot of flickering in comination with mini.animate ([495f36a](https://github.com/folke/edgy.nvim/commit/495f36ae6db677bb9539e2cc3fc2ab79358cc058))
* **window:** only update height/width when needed ([004a097](https://github.com/folke/edgy.nvim/commit/004a09763ed8b2fe45f3752e8275434a6756e6e9))