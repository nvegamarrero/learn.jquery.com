---
chapter : effects
section : 4
title   : Managing Effects
attribution:  jQuery Fundamentals
---
## Managing Effects

jQuery provides several tools for managing animations.

### `$.fn.stop`

Stop currently running animations on the selected elements.

### `$.fn.delay`

Wait the specified number of milliseconds before running the next animation.

<javascript>
$('h1').show(300).delay(1000).hide(300);
</javascript>

### `jQuery.fx.off`

If this value is true, there will be no transition for animations; elements
will immediately be set to the target final state instead.  This can be
especially useful when dealing with older browsers; you also may want to
provide the option to your users.
