# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for **Qinghai University High-Performance and Cloud Computing Research Institute** (青海大学高性能与云计算研究所 / qhuHdaCC). The site currently has no backend or build system.

## Structure

- `index.html` - Main entry point (currently empty - under development)
- `static/plugin/` - Third-party libraries:
  - `layui/` - Layui CSS/JS framework (v2.x)
  - `echarts.min.js` - ECharts visualization library

## Development

No build process required. Open `index.html` directly in a browser or serve with any static file server:

```bash
# Python
python -m http.server 8080

# Node.js (npx)
npx serve .
```

## Notes

- All Chinese text in the codebase is encoded in UTF-16 LE (with BOM)
- The project is in early development stage