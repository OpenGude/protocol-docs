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
