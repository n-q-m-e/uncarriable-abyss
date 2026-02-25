# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [0.2.0] - 2026-02-26

### Added
- Procedural FBM clouds in sky (4 octaves, drifting)
- Animated caustic light patterns in wave troughs
- God rays post-process (radial blur from sun)
- Richer turquoise/emerald water palette
- Stronger subsurface scattering colors

### Changed
- Fog now blends to sky horizon color (seamless water-sky transition)
- Sun intensity reduced across water and sky shaders
- Detail normals optimized (6 noise calls instead of 9)
- God rays optimized (8 samples instead of 30)
- Quadratic fog falloff for cleaner horizon blend

## [0.1.0] - 2026-02-26

### Added
- Three.js ocean scene with 4-layer Gerstner wave displacement
- Custom GLSL vertex + fragment shaders
- Fresnel-based sky reflections on water surface
- Subsurface scattering effect on wave crests
- Wispy organic foam (3-layer procedural noise)
- Procedural sky dome with morning gradient
- Animated sun position (slowly rising)
- Extended sun path on water (3-tier specular)
- Atmospheric haze blending at horizon
- Depth variation patches simulating seabed
- Scrolling detail ripple normals
- Film grain + vignette post-processing
- Subtle camera floating drift
- Responsive viewport (desktop + mobile)
