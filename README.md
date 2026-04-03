# AmDisplay Lite

**FREE Amazon product display plugin for WordPress**

[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/gpl-2.0)

## Description

AmDisplay Lite is a powerful WordPress plugin that displays Amazon products using the official Amazon API. Perfect for affiliate marketers looking to monetize their content.

### ✨ Features

- 🎨 **3 Beautiful Templates** – Box, Compact, and List templates
- 🌍 **Geolocation** – Automatically redirects visitors to their local Amazon store
- 🔌 **Amazon API Integration** – Supports PA-API 5.0 and Creators API (OAuth 2.0)
- 📦 **50 Product Displays Per Month** – Perfect for small sites
- ⚡ **Smart Caching** – Configurable cache for faster page loads
- 🔧 **Shortcode Generator** – Easy-to-use interface
- 🔐 **Secure** – API keys encrypted with WordPress salts

## Installation

1. Upload the `amdisplay` folder to `/wp-content/plugins/`
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to **AmDisplay Lite → Settings** to configure your Amazon API credentials
4. Enter your free license key: `APD-FREE-2026`
5. Start using shortcodes

### Shortcode Examples

```php
[amdisplay asin="B002QYW8LW"]

[amdisplay asin="B002QYW8LW" template="compact"]

[amdisplay asin="B002QYW8LW" template="list" align="center"]
