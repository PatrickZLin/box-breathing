# Breathe

A minimalist web application for the Box Breathing (4-4-4-4) technique.

## 📱 Mobile Experience

To use this as a native-feeling app on your phone:

1.  Navigate to your deployed site link on your phone.
2.  **iOS (Safari):** Tap Share → "Add to Home Screen".
3.  **Android (Chrome):** Tap Menu (3 dots) → "Install App" or "Add to Home Screen".

## 🛠 Customization

You can adjust the breathing timing by editing the `phases` array inside the `<script>` tag:

```javascript
const phases = [
    { text: "Inhale", time: 4000 }, // Time in milliseconds
    { text: "Hold", time: 4000 },
    { text: "Exhale", time: 4000 },
    { text: "Hold", time: 4000 }
];
