# BLÜM · Revenue

Presupuesto trimestral, tarifas recomendadas, aseo semanal e informe diario de Claude para los inmuebles de BLÜM GROUP.

- **App (este repo, público):** solo `index.html`. Publícalo con GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).
- **Datos (repo privado `BLUM-REVENUE-DATA`):** `data/state.json` (lo escribe la app), `data/research.json`, `data/market-claude.json` y `data/reports/AAAA-MM-DD.json` (los escribe Claude cada mañana a las 8:23 a. m.).

## Conectar la app a los datos
1. Crea un token fine-grained: GitHub → Settings → Developer settings → Fine-grained tokens → Generate. Repository access: **Only select repositories → BLUM-REVENUE-DATA**. Permissions → Repository → **Contents: Read and write**.
2. Abre la app → Ajustes → **Conectar GitHub** → usuario `BlumGroup`, repo `BLUM-REVENUE-DATA`, token.
3. El token queda solo en ese navegador. Repite el paso 2 en cada equipo o celular donde uses la app.

No pongas datos en este repo público.
