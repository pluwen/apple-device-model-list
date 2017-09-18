# iOS_Device_Detect
Detect iOS Device based on Device Model.

```if ([platform isEqualToString:@"iPhone2,1"]) return @"iPhone 3GS";
if ([platform isEqualToString:@"iPhone3,1"]) return @"iPhone 4";
if ([platform isEqualToString:@"iPhone3,2"]) return @"iPhone 4";
if ([platform isEqualToString:@"iPhone3,3"]) return @"iPhone 4";
if ([platform isEqualToString:@"iPhone4,1"]) return @"iPhone 4S";
if ([platform isEqualToString:@"iPhone5,1"]) return @"iPhone 5";
if ([platform isEqualToString:@"iPhone5,2"]) return @"iPhone 5";
if ([platform isEqualToString:@"iPhone5,3"]) return @"iPhone 5c";
if ([platform isEqualToString:@"iPhone5,4"]) return @"iPhone 5c";
if ([platform isEqualToString:@"iPhone6,1"]) return @"iPhone 5s";
if ([platform isEqualToString:@"iPhone6,2"]) return @"iPhone 5s";
if ([platform isEqualToString:@"iPhone7,1"]) return @"iPhone 6 Plus";
if ([platform isEqualToString:@"iPhone7,2"]) return @"iPhone 6";
if ([platform isEqualToString:@"iPhone8,1"]) return @"iPhone 6S";
if ([platform isEqualToString:@"iPhone8,2"]) return @"iPhone 6S Plus";
if ([platform isEqualToString:@"iPhone8,4"]) return @"iPhone SE";
if ([platform isEqualToString:@"iPhone9,1"]) return @"iPhone 7";
if ([platform isEqualToString:@"iPhone9,2"]) return @"iPhone 7 Plus";
if ([platform isEqualToString:@"iPhone9,3"]) return @"iPhone 7";
if ([platform isEqualToString:@"iPhone9,4"]) return @"iPhone 7 Plus";

if ([platform isEqualToString:@"iPod4,1"]) return @"iPod touch 4";
if ([platform isEqualToString:@"iPod5,1"]) return @"iPod touch 5";
if ([platform isEqualToString:@"iPod7,1"]) return @"iPod touch 6";

if ([platform isEqualToString:@"iPad2,1"]) return @"iPad 2";
if ([platform isEqualToString:@"iPad2,2"]) return @"iPad 2";
if ([platform isEqualToString:@"iPad2,3"]) return @"iPad 2";
if ([platform isEqualToString:@"iPad2,4"]) return @"iPad 2";
if ([platform isEqualToString:@"iPad2,5"]) return @"iPad mini";
if ([platform isEqualToString:@"iPad2,6"]) return @"iPad mini";
if ([platform isEqualToString:@"iPad2,7"]) return @"iPad mini";

if ([platform isEqualToString:@"iPad3,1"]) return @"iPad 3";
if ([platform isEqualToString:@"iPad3,2"]) return @"iPad 3";
if ([platform isEqualToString:@"iPad3,3"]) return @"iPad 3";
if ([platform isEqualToString:@"iPad3,4"]) return @"iPad 4";
if ([platform isEqualToString:@"iPad3,5"]) return @"iPad 4";
if ([platform isEqualToString:@"iPad3,6"]) return @"iPad 4";

if ([platform isEqualToString:@"iPad4,1"]) return @"iPad Air";
if ([platform isEqualToString:@"iPad4,2"]) return @"iPad Air";
if ([platform isEqualToString:@"iPad4,3"]) return @"iPad Air";
if ([platform isEqualToString:@"iPad4,4"]) return @"iPad mini 2";
if ([platform isEqualToString:@"iPad4,5"]) return @"iPad mini 2";
if ([platform isEqualToString:@"iPad4,6"]) return @"iPad mini 2";
if ([platform isEqualToString:@"iPad4,7"]) return @"iPad mini 3";
if ([platform isEqualToString:@"iPad4,8"]) return @"iPad mini 3";
if ([platform isEqualToString:@"iPad4,9"]) return @"iPad mini 3";

if ([platform isEqualToString:@"iPad5,1"]) return @"iPad mini 4";
if ([platform isEqualToString:@"iPad5,2"]) return @"iPad mini 4";
if ([platform isEqualToString:@"iPad5,3"]) return @"iPad Air 2";
if ([platform isEqualToString:@"iPad5,4"]) return @"iPad Air 2";

if ([platform isEqualToString:@"iPad6,3"]) return @"iPad Pro 9.7";
if ([platform isEqualToString:@"iPad6,4"]) return @"iPad Pro 9.7";
if ([platform isEqualToString:@"iPad6,7"]) return @"iPad Pro 12.9";
if ([platform isEqualToString:@"iPad6,8"]) return @"iPad Pro 12.9";

if ([platform isEqualToString:@"AppleTV5,3"]) return @"Apple TV";

if ([platform isEqualToString:@"i386"]) return @"iPhone Simulator";
if ([platform isEqualToString:@"x86_64"]) return @"iPhone Simulator";
```

### Unsupport iOS6

```if ([platform isEqualToString:@"iPhone1,1"]) return @"iPhone";
if ([platform isEqualToString:@"iPhone1,2"]) return @"iPhone 3G";
if ([platform isEqualToString:@"iPad1,1"]) return @"iPad";
if ([platform isEqualToString:@"iPod1,1"]) return @"iPod touch";
if ([platform isEqualToString:@"iPod2,1"]) return @"iPod touch 2";
if ([platform isEqualToString:@"iPod3,1"]) return @"iPod touch 3";
```
