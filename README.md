bootstrap-no-responsive
=======================

Compiled Bootstrap with responsive features disabled.

**Current Bootstrap version:** 3.1.1

### Changes

`variables.less` changed as follows:

```
// Media queries breakpoints
// --------------------------------------------------

// Extra small screen / phone
// Note: Deprecated @screen-xs and @screen-phone as of v3.0.1
@screen-xs:                  1px;
@screen-xs-min:              @screen-xs;
@screen-phone:               @screen-xs-min;

// Small screen / tablet
// Note: Deprecated @screen-sm and @screen-tablet as of v3.0.1
@screen-sm:                  2px;
@screen-sm-min:              @screen-sm;
@screen-tablet:              @screen-sm-min;

// Medium screen / desktop
// Note: Deprecated @screen-md and @screen-desktop as of v3.0.1
@screen-md:                  3px;
@screen-md-min:              @screen-md;
@screen-desktop:             @screen-md-min;

// Large screen / wide desktop
// Note: Deprecated @screen-lg and @screen-lg-desktop as of v3.0.1
@screen-lg:                  9999px;
@screen-lg-min:              @screen-lg;
@screen-lg-desktop:          @screen-lg-min;
```

### Installation

Installed as a [Bower](http://bower.io) package. Add as a dependency in `bower.json`:

```
...
"dependencies": {
	"bootstrap-no-responsive": "indragiek/bootstrap-no-responsive.git#3.1.1"
	...
}
```
