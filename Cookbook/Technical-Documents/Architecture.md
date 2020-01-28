ProjectX iOS Architecture
========================

## Overview

In ProjectX, we use [VIPER](https://www.objc.io/issues/13-architecture/viper/) architecture pattern to develop each UI screen and its business logic.
The most common VIPER practice in iOS is to treat `UIViewController` as `View`, which holds `Presenter` to delegate the event and business logic handling to decouple from `View`'s primary goal of "rendering its appearance".
