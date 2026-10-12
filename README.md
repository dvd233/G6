# G6 #7671 reproduction screenshots

Rendered from the current source UMD builds in Chromium 143 with the issue's four-node, three-edge example and animations disabled.

- `before.png`: upstream `e825d0980e952edb42e7cee2e335e32d64256619`.
- `after.png`: the Dagre control-point conversion fix; `layout.ts` SHA-256 `5e262148562eade3e205a60b629ab6f533af2436fae7941c12be76418c9738d8`.
- Fixed UMD SHA-256: `04773181444a1f8a858e51c82feed6e34a8e15a4b2c07eef9bee19a3e7615f00`.

These images show the LR direction. Separate measurements cover LR/RL/TB/BT (three edges per direction): the fixed paths have a nonzero final segment and aligned arrow direction. The example's unregistered `drag-node` warning remains; dragging and animation were not verified by this screenshot probe.
