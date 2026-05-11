# Vanish iOS App — Info

## App Store Connect
- **App Name**: Vanish
- **Bundle ID**: `com.geekmagnetinc.vanish`
- **Apple ID**: TBD — fill after App Store Connect entry exists
- **SKU**: vanish-ios
- **Primary Language**: English (U.S.)
- **Platform**: iOS

## Apple Developer
- **Team ID**: L52G64VBAZ
- **Account Holder (Owner)**: Kristin Boster (kristin@kristinboster.com)
- **Developer (Chandler)**: hero88go@gmail.com — under Kristin's account
- **Company**: Geek Magnet Inc

## Codemagic
- **Project**: vanish-ios (TODO: create)
- **Repo**: github.com/Hero88go/vanish-ios (TODO: create)
- **Provisioning Profile name**: `vanish-profile`
- **Distribution Cert name**: `vanish-distribution`

## Local Setup (one-time)
```
cd "c:/Users/Chandler/NEW project/vanish-ios"
npm install
npx cap add ios
npx cap sync ios
```

## Asset Pipeline
- Replace `assets/icon.png` with a 1024x1024 PNG branded for Vanish
- Then: `npx @capacitor/assets generate --ios`

## Web Source
- Source HTML: `c:/Users/Chandler/NEW project/vanish.html`
- iOS-shipped copy: `www/index.html` (viewport patched for safe-area-inset)

## App Store Description (draft)
**Subtitle**: Word memory game
**Description**:
Words appear, then vanish. Recall them. Test your verbal memory in a minimal, ghostly interface.

## Notes
- Pure local game — no backend.
