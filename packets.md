# Packets

## processLogin (10)

```
int: timestamp
obj: locale (string)
```

## procReloginAndRetry (11)

```
int: timestamp
obj: locale (string)
```

## sendReceiptDirect (23)

```
int: isConsume (bool)
obj: receipt (string)
```

## checkPushToken (25)

```
obj: token (string)
```

## ping (59)

No parameters

## goOpeningScene (77)

No parameters

## procAppsFlyer (119)

```
obj: id (string)
```

## ??? (190)

No parameters

This is common - some kind of continuation?

## setTutorialProgress (204)

```
int: tutorialProgress
```

## ??? (229)

```
int: num
```

Something to do with Offerwall promotions?

## completeTutorial (16777423 - 0x10000CF)

No parameters

## triggeredDecideButton (100663307 - 0x600000B)

No parameters

## checkFirstLoginInfo (100663309 - 0x600000D)

```
obj: info (FirstLoginInfo)
```

## processDebugLogin (117441511 - 0x70003E7)

```
int: rank
```

This name might not be very accurate.

## cancelCooling (134217910 - 0x80000B6)

```
int: kitchenwareType
```

## triggeredUseButton (134217911 - 0x80000B7)

```
int: [kitchenwareType,currentIndex]
```

"HurryUpMetal"

## triggeredUsefulUseButton (134217971 - 0x80000F3)

```
int: [kitchenwareType,usefulId]
```

"HurryUpItem"

## triggeredUseButton (134217976 - 0x80000F8)

```
int: [kitchenwareType,usefulId,currentIndex]
```

"HurryUpUsually"
