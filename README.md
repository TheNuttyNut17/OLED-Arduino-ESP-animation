# Video to Arduino OLED Converter

Convert short videos into ready-to-use Arduino code for OLED displays. This web application processes video files and generates optimized Arduino sketches that can be directly copied and pasted into the Arduino IDE.

## Features

- **Video Processing**: Upload MP4, AVI, MOV, or MKV files
- **Multiple Display Sizes**: Support for 128x64, 96x64, 128x32, 64x48, and custom sizes
- **Multiple Libraries**: Adafruit GFX + SSD1306, Adafruit GFX + SSD1331, and U8g2
- **Real-time Preview**: See your video animation on a simulated OLED display
- **Automatic Code Generation**: Arduino code is automatically generated when video processing completes
- **Ready-to-Use Code**: Complete Arduino sketches with all frame data included

## How It Works

1. **Upload Video**: Select your video file (supports common formats)
2. **Configure Display**: Choose OLED size, orientation, and Arduino library
3. **Process Frames**: Video is converted to monochrome frames optimized for Arduino
4. **Preview Animation**: See how your video will look on the OLED display
5. **Copy Code**: Automatically generated Arduino code is ready to copy/paste



This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
