# Transliterator Plugin for QGIS

## 📌 Overview
The **Transliterator Plugin** recognizes the **Georgian alphabet** and transliterates it into **Latin script** within a newly created field in a vector layer.

## 🔥 Features
- Automatically detects **Georgian text** in the selected field.
- Creates a **new field** with the transliterated Latin text.
- Ensures the original field supports **Georgian fonts**.
- **Shapefile compatibility warning**: Field names are limited to **10 characters**, so the script appends `"_lat"` to the new field name.
- Works seamlessly within **QGIS**.

## ⚠️ Important Notes
- If using **Shapefiles**, make sure your field name is **short enough** (max **8 characters**), as the plugin adds `"_lat"` to the new field name.
- If you need longer field names, consider using **GeoPackage (GPKG) or PostgreSQL** instead of Shapefiles.

## 🛠️ Installation
1. Download or clone the plugin repository.
2. Load the plugin in **QGIS** from the **Plugin Manager**.
3. Select a **layer** and a **field** to transliterate.
4. Click **Run Transliteration**.

## 🚀 Usage
1. Open **QGIS** and load a vector layer.
2. Open the **Transliterator Plugin**.
3. Select a **layer** and choose a **field** containing Georgian text.
4. Click **Run Transliteration**.
5. A new field will be created with the **Latin transliteration**.

## 📜 Example
**Input:** `საქართველო` → **Output:** `saqarTvelo`
**Input:** `თბილისი` → **Output:** `Tbilisi`
**Input:** `ჭიათურა` → **Output:** `WiaTura`
**Input:** `ქუჩა` → **Output:** `quCa`
**Input:** `შესახვევი` → **Output:** `Sesaxvevi`
**Input:** `ჩიხი` → **Output:** `Cixi`
**Input:** `ჭიათურა` → **Output:** `WiaTura`
**Input:** `ჭიათურა` → **Output:** `WiaTura`
            

## 🏆 Credits
Developed by **[Kapanadze]** for simplifying transliteration in GIS projects.

## 📧 Support
For issues or suggestions, feel free to **open an issue** or **contact me**.

Happy Mapping! 🌍✨

