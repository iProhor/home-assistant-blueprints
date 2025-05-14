# Motion or Manual Light Control at Night (with Resettable Timeout)

🏠 **Home Assistant Blueprint**  
Automatically control a light based on motion sensor **only at night**.  
Also supports **manual light activation** and ensures the light turns off after a timeout if **no motion is detected**.  
Timeout is **reset** on each new motion event.

## ✅ Features

- Motion turns on light **only between sunset and sunrise**
- Manual turn-on supported (light still turns off later)
- Turns off after timeout when no motion is detected
- Timeout is reset if motion is detected again

## 🔧 Required Inputs

- Motion sensor (`binary_sensor`)
- Light entity (actual `light.xyz`)
- Timeout value in seconds

## 🧠 How to Use

1. Go to **Home Assistant → Settings → Automations & Scenes → Blueprints**
2. Click **Import Blueprint**, paste the raw URL of `blueprint.yaml`:
   ```
   https://raw.githubusercontent.com/your-user/home-assistant-blueprints/main/motion_manual_light_night/blueprint.yaml
   ```
3. Click “Import Blueprint”
4. Create a new automation based on it and set the motion sensor, light entity, and timeout.

## 📝 Author

Oleg Lugovskiy  
MIT License
