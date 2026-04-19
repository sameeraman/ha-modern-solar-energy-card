# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2026-04-19

### Added
- Battery state of charge (SOC) display with percentage text
- Battery charge/discharge power display (W/kW)
- Color-coded battery SOC progress bar (green → yellow → orange → red based on charge level)
- EV charger power consumption display (W/kW)
- Animated pulse flow for battery charging (inverter → battery)
- Animated pulse flow for battery discharging (battery → inverter)
- Animated pulse flow for EV charger (inverter → charger)
- Smart visibility rules: battery/charger animations show/hide based on active power state
- New SVG file (`hasolardashboard-modenhouse-v2.svg`) with battery and EV charger elements

### Changed
- Updated SVG reference from v1 to v2
- Expanded YAML configuration with battery and charger sensor rules

## [1.0.0] - 2025-06-02

### Added
- Initial release
- Real-time solar power flow visualization
- Home consumption monitoring
- Grid exchange visualization
- Automatic unit conversion (W to kW)
- Responsive design
- Tesla-inspired modern UI
