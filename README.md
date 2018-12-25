# Toast

A Flutter Toast plugin.

> Supported  Platforms
> * Android 
> fix BadTokenException and no notification permission required
> * IOS
> use https://github.com/scalessec/Toast-Swift


## How to Use

```yaml
# add this line to your dependencies
toast: ^0.0.1
```

```dart
import 'package:toast/toast.dart';
```

```dart
Toast.show("Toast plugin app", duration: Toast.LENGTH_SHORT, gravity:  Toast.BOTTOM);
```

property | description
--------|------------
msg | String (Not Null)(required)
duration| Toast.LENGTH_SHORT or Toast.LENGTH_LONG (optional)
gravity | Toast.TOP (or) Toast.CENTER (or) Toast.BOTTOM
timeInSecForIos | int (only for ios)


![toast](https://github.com/huclengyue/FlutterToast/blob/master/screenshot/141107.png)
![toast](https://github.com/huclengyue/FlutterToast/blob/master/screenshot/141134.png)

## License

   MIT License

   Copyright (c) 2018 YM

   Permission is hereby granted, free of charge, to any person obtaining a copy
   of this software and associated documentation files (the "Software"), to deal
   in the Software without restriction, including without limitation the rights
   to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
   copies of the Software, and to permit persons to whom the Software is
   furnished to do so, subject to the following conditions:
