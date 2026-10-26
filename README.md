### Hi, I'm Christopher Knight · Geospatial data engineering for AI agents

I turn complex spatial data into reliable systems that AI agents can reason over: parcels and deeds, flood zones, census demographics and environmental monitoring. I build tested pipelines with PostGIS, DuckDB and dbt, run audit-first quality checks that never change data silently, and expose the results through MCP servers with governed, read-only tools.

---

#### What I build

- **GIS data QA and repair.** Geometry, topology, CRS and attribute checks with every change logged and source data never modified.
- **Agent-ready data.** MCP servers (FastMCP) over DuckDB and PostGIS, with read-only tools and governed metric definitions instead of free-form SQL.
- **Tested pipelines.** dbt staging → marts with data tests, scheduled runs on GitHub Actions, static dashboards on GitHub Pages.

---

#### Featured work

| Project | What it does |
|---|---|
| **[GeoRescue](https://github.com/knightchrism/georescue)** · [live dashboard ↗](https://knightchrism.github.io/georescue/) | Parcel QA that checks recorded deeds against GIS: deed OCR, metes-and-bounds parsing and COGO traverses tied to PLSS corners, plus the **Ask GeoRescue** MCP server. |
| **[census-pipeline](https://github.com/knightchrism/census-pipeline)** | Census ACS → DuckDB → dbt (tests and docs) → governed metrics served to agents by a FastMCP server. Covers 67 Florida counties. |
| **[jax-property-mcp](https://github.com/knightchrism/jax-property-mcp)** | MCP server and local tool-calling agent over 405k Duval County parcels in PostGIS, with FEMA flood-zone overlay and dbt-tested models. |
| **[jax-property-intelligence](https://github.com/knightchrism/jax-property-intelligence)** | PostgreSQL/PostGIS property platform for parcel, sales, zoning and flood analysis. |
| **[sjrwmd-geodata-qc](https://github.com/knightchrism/sjrwmd-geodata-qc)** · [dashboard ↗](https://knightchrism.github.io/sjrwmd-geodata-qc/) | Rule-based QA/QC of 850 groundwater monitoring stations from an ArcGIS REST service, reviewed on an interactive Leaflet map. |

---

#### Stack

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00e5ff) ![MCP](https://img.shields.io/badge/MCP-0d1117?style=flat-square&logo=anthropic&logoColor=00e5ff) ![Ollama](https://img.shields.io/badge/Ollama-0d1117?style=flat-square&logo=ollama&logoColor=00e5ff) ![PostGIS](https://img.shields.io/badge/PostGIS-0d1117?style=flat-square&logo=postgresql&logoColor=00e5ff) ![DuckDB](https://img.shields.io/badge/DuckDB-0d1117?style=flat-square&logo=duckdb&logoColor=00e5ff) ![dbt](https://img.shields.io/badge/dbt-0d1117?style=flat-square&logo=dbt&logoColor=00e5ff) ![GeoPandas](https://img.shields.io/badge/GeoPandas-0d1117?style=flat-square&logo=pandas&logoColor=00e5ff) ![Shapely](https://img.shields.io/badge/Shapely-0d1117?style=flat-square&logoColor=00e5ff) ![GDAL](https://img.shields.io/badge/GDAL-0d1117?style=flat-square&logoColor=00e5ff) ![Leaflet](https://img.shields.io/badge/Leaflet-0d1117?style=flat-square&logo=leaflet&logoColor=00e5ff) ![Streamlit](https://img.shields.io/badge/Streamlit-0d1117?style=flat-square&logo=streamlit&logoColor=00e5ff) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=flat-square&logo=githubactions&logoColor=00e5ff)

---

<p>
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=knightchrism&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00e5ff&icon_color=00e5ff&text_color=c9d1d9&hide=stars" alt="GitHub stats" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=knightchrism&layout=compact&hide_border=true&bg_color=0d1117&title_color=00e5ff&text_color=c9d1d9" alt="Top languages" />
</p>

---

**Open to AI engineering roles**, especially agent tooling, MCP and geospatial data.  
[GitHub](https://github.com/knightchrism) · [GeoRescue](https://knightchrism.github.io/georescue/)
