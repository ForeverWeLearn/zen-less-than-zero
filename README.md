<h1 align="center">
    <strong><i>Zen < 0</i></strong>
</h1>

<p align="center"><i>It's empty and it is.</i></p>

<img align="center" src="imgs/zen-custom.png" />

<div align="center">
    🫥 &ensp;•&ensp; 💔 &ensp;•&ensp; ✨
</div>

&nbsp;

<p align="center"><i>Zen is minimal by default. But we can move one step further 🤓</i></p>

<img align="center" src="imgs/infographic.png" />

&nbsp;

## ***Motivation*** 🫸

Modern features and dense UI not quite interesting. So hide it.

&nbsp;

## ***Quick setup*** 🏃‍➡️

Here's short version of [userChrome.css](userChrome.css) with comments removed. Copy and paste it to yours. DONE!

```css
#zen-sidebar-top-buttons,
#zen-sidebar-foot-buttons,
#zen-overflow-extensions-list,
#zen-essentials,
#zen-media-controls-toolbar,
.zen-current-workspace-indicator,
.pinned-tabs-container-separator {
    visibility: collapse;
}

#nav-bar {
    position: absolute !important;
    margin-top: -99px;
}

#titlebar {
    padding-top: 4px !important;
}
```

&nbsp;

## ***Full setup*** 🧭

**Step 1:** Turn on Zen *live editing* feature.

Follow the guide https://docs.zen-browser.app/guides/live-editing

**Step 2:** Copy it [userChrome.css](userChrome.css) and done.

