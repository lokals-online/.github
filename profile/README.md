1. **Platform Description**:

- A Turkish online gaming platform focused on traditional coffee house games
- Available on both iOS and Android through native apps
  - https://play.google.com/store/apps/details?id=com.ersanceylan.lokalsonline
  - https://apps.apple.com/us/app/lokalsonline/id6499447614
- Also has a web presence at lokals.online

2. **Technical Stack**:

- React Native/Expo for cross-platform mobile development
- Firebase for backend services (Authentication, Firestore, Functions)
- TypeScript for type safety
- Uses Skia for custom graphics/animations

3. **Key Features**:

- QR code-based game sharing/joining system
- Multiple traditional Turkish games including:
  - Tavla (Backgammon) with variants (Hapis, Hepyek, Mülteci)
  - Batak
  - Pişti
  - King
  - Mangala
  - Dama
- Virtual assistant called "Çırak" (apprentice) that helps users
- Social features including voice messaging for Pro users

4. **Architecture**:

- Firebase hosting configuration for both app and static content
- Separate builds for development, staging and production
- Uses Firebase Cloud Functions for backend logic
- Implements deep linking for both iOS and Android

5. **Monetization**:

- Has "Pro" and "Bro" account types
- In-app currency called "marka"
- Integrated with in-app purchases

<!-- The project appears to be a well-structured modern mobile application that digitizes traditional Turkish games while maintaining their social aspects through features like voice chat and QR code-based matchmaking. -->
