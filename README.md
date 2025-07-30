# AlaxCAD

**AlaxCAD** is a free, open-source CAD system for FiveM inspired by SonoranCAD.  
It features:

- 🚔 NUI-based dispatcher panel (Sonoran-style UI)
- 🗺️ Live unit map using Leaflet + in-game coordinates
- 🏷️ DMV plate lookup connected to MySQL
- 🛣️ In-game street names with `GetStreetNameAtCoord()`
- 🌐 Web-based dispatcher panel (browser access)

### 🛠 Setup
1. Import `sql/alaxcad.sql` into your MySQL database
2. Install [oxmysql](https://github.com/overextended/oxmysql)
3. Add `ensure alaxcad` to your `server.cfg`
4. Customize `config.lua` to your department setup
5. Launch the game or access `/web_dispatch/index.html` for browser dispatch panel

---

Need help? Open an issue or join our community.
