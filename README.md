# Zia Split Tabs

Standalone extraction from [Zia](https://github.com/z1n-k/zia), MIT licensed.

Drag a tab onto the page, then toward either edge and drop. Dragging the current tab adds a new-tab pane.

The native split-drop default is disabled for the browser session to avoid competing drop targets. If you explicitly enabled `zen.splitView.enable-tab-drop` in about:config, set it to false. Disable this mod and restart to restore the native default.

## Install

Requires Zen Browser and [Sine](https://github.com/CosmoCreeper/Sine). This includes JavaScript and cannot run as a CSS-only Zen store mod.

1. In Zen Settings → Sine Mods, enable installing JavaScript from unofficial sources.
2. Enter `natsufatsu/zia-split-tabs` in Sine's install box.
3. Disable the original full Zia mod, then restart Zen. The two extracted mods can run together or separately.

Restart after enabling, disabling or updating these JavaScript mods. If necessary, clear the startup cache in `about:support`.

The ZIP is a repository-ready package; it is not a Firefox extension/XPI. Repository: https://github.com/natsufatsu/zia-split-tabs

## 1.0.4

Keeps the animated split targets and uses Zen's rectangular icon-and-title preview over the page. Restores the sidebar-shaped preview when moving back out. Reuses Zen's built-in preview styling, with no screenshots, floating canvas or scroll tracking.

Update the mod in Sine and restart Zen to apply this version.

## Validation

JavaScript syntax and package dependencies checked locally. Live Zen interaction and visual checks are still required, especially on Windows and Linux.
