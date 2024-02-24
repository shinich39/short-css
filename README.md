## short-css

Short stylesheet.

## Usage

```css
.d-n{display: none;}
.d-i{display: inline;}
.d-ib{display: inline-block;}
.d-b{display: block;}
.d-f{display: flex;}
...
.b-0{border: 0px solid black;}
.b-1{border: 1px solid black;}
.b-2{border: 2px solid black;}
...
.bt-4{border-top: 4px solid black;}
.bt-5{border-top: 5px solid black;}
.bt-6{border-top: 6px solid black;}
...
.f-0{flex: none;}
.f-1{flex: 1;}
.f-2{flex: 2;}
...
.fd-r{flex-direction: row;}
.fd-rr{flex-direction: row-reverse;}
.fd-c{flex-direction: column;}
.fd-cr{flex-direction: column-reverse;}
...
/* fx: axis x algin items in flex */
/* fy: axis y align items in flex */
/* s: start, c: center, e: end, st: stretch */
.fx-s{justify-content: start;}
.fx-st{justify-content: stretch;}
.fy-s{align-items: start;}
.fy-st{align-items: stretch;}
...
.w-0{width: 0;}
.w-1{width: 8.33%;}
.w-2{width: 16.66%;}
.w-3{width: 25%;}
.w-4{width: 33.33%;}
.w-5{width: 41.66%;}
.w-6{width: 50%;}
.w-7{width: 58.33%;}
.w-8{width: 66.66%;}
.w-9{width: 75%;}
.w-10{width: 82.33%;}
.w-11{width: 91.66%;}
.w-12{width: 100%;}
.w-100{width: 100%;}
...
.m-1{margin: 1rem;}
.m-2{margin: 2rem;}
.m-3{margin: 3rem;}
...
.m-06{margin: 0.6rem;}
.m-07{margin: 0.7rem;}
.m-08{margin: 0.8rem;}
...
.mt-19{margin-top: 1.9rem;}
.mt-20{margin-top: 2.0rem;}
.mt-21{margin-top: 2.1rem;}
...
.pb-43{padding-bottom: 4.3rem;}
.pb-44{padding-bottom: 4.4rem;}
.pb-45{padding-bottom: 4.5rem;}
...
.fc-7{color: #777777;}
.fc-8{color: #888888;}
.fc-9{color: #999999;}
...
.fs-27{font-size: 2.7rem;}
.fs-28{font-size: 2.8rem;}
.fs-29{font-size: 2.9rem;}
...
.fw-5{font-weight: 500;}
.fw-6{font-weight: 600;}
.fw-7{font-weight: 700;}
...
.lh-14{line-height: 1.4rem;}
.lh-15{line-height: 1.5rem;}
.lh-16{line-height: 1.6rem;}
...
.ws-12{word-spacing: 0.12rem;}
.ws-13{word-spacing: 0.13rem;}
.ws-14{word-spacing: 0.14rem;}
...
.ls-12{letter-spacing: 0.12rem;}
.ls-13{letter-spacing: 0.13rem;}
.ls-14{letter-spacing: 0.14rem;}
...
.bg-8{background-color: #888888;}
.bg-9{background-color: #999999;}
.bg-a{background-color: #aaaaaa;}
...
.pe-n{pointer-events: none;}
...

```

```html
<!-- flex: column -->
<div class="d-f fd-c fx-e fy-c h-8">
  <div class="w-2 b-1">
    ITEM 1
  </div>
  <div class="f-n b-1">
    ITEM 2
  </div>
  <div class="w-2 b-1">
    ITEM 3
  </div>
</div>

<!-- flex: row -->
<div class="d-f fd-r fx-s fy-c h-8">
  <div class="w-2 b-1">
    ITEM 1
  </div>
  <div class="f-n b-1">
    ITEM 2
  </div>
  <div class="w-2 b-1">
    ITEM 3
  </div>
</div>

<!-- font-size: 1.2rem -->
<div class="fs-12"></div>

<!-- font-color: #FFFFFF; -->
<div class="fc-f"></div>

<!-- display: none; -->
<div class="d-n"></div>
```