# Smart Lock with Web Dashboard

A Wi-Fi door lock built on an ESP32. You lock and unlock it from a web page,
and every action is saved to a log.

**Status:** In progress (started November 2026)

## Plan

1. ESP32 connects to Wi-Fi and serves a small web page
2. Lock and unlock buttons on the page (the onboard LED stands in for the lock)
3. Log every lock and unlock with a timestamp, and show the log on the page
4. Replace the LED with a servo or relay that moves a real latch
5. Add a PIN so only authorized users can unlock

## Hardware

- ESP32 development board
- Servo or relay module (later step)

## Built with

- C++ (Arduino framework)
- HTML and JavaScript for the dashboard
