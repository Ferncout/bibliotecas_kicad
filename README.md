# Bibliotecas KiCad — Componentes Customizados

Repositório pessoal de símbolos esquemáticos (`.kicad_sym`), footprints (`.kicad_mod`) e modelos 3D (`.step`) validados e ajustados para módulos de desenvolvimento, transceptores RF e periféricos utilizados em projetos de hardware e PCBs.

---

## Catálogo de Componentes

| Componente | Categoria | Footprint | Modelo 3D | Observações |
| :--- | :--- | :--- | :---: | :--- |
| **ESP32-S3-DevKitC-1 (N16R8)** | Microcontroladores | `ESP32-S3-N16R8_44P` | Sim | Revisão de **44 pinos** (22 por fileira), passo `2.54 mm`, pinagem ordenada conforme serigrafia física. |
| *(Ex: LoRa E220-900T30D)* | *Módulos RF* | *`E220-900T30D`* | *Sim* | *Pinagem UART + M0/M1/AUX.* |

---

## Estrutura do Repositório

```text
bibliotecas_kicad/
├── symbols/        # Bibliotecas de símbolos esquemáticos (.kicad_sym)
├── footprints/     # Bibliotecas de footprints (.pretty / .kicad_mod)
├── 3dmodels/       # Modelos mecânicos 3D (.step / .wrl)
└── assets/         # Diagramas de pinout, capturas 3D e datasheets de referência
