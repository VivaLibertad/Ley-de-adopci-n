Estudio Cuantitativo: Ley de Agilización de la Adopción en Ecuador

Análisis predictivo y comparativo sobre el impacto de la Ley Orgánica Reformatoria para la Agilización de la Adopción en Ecuador (Registro Oficial No. 347-S, 14 ago 2026).

Metodología: Legal-BERT (NLP) · Random Forest / Prophet (predictivo) · Sentence-BERT (comparativa semántica) · Análisis estadístico multivariable.

👉 Ver el análisis completo en reporte_estudio_completo.md.

Contenido del repositorio
Archivo	Tipo	Descripción
estudio_adopciones_ecuador_completo.py	Python	Script completo ejecutable
data/df_adopciones_ecuador.csv	CSV	Adopciones históricas Ecuador
data/df_comparativa_regional.csv	CSV	Comparativa 5 países
data/df_proyecciones_2026_2030.csv	CSV	Proyecciones Prophet
data/df_nlp_analisis_legalbert.csv	CSV	Scores NLP por artículo
data/df_random_forest_features.csv	CSV	Feature importance
data/df_impacto_economico.csv	CSV	Análisis costo-beneficio
data/df_timeline_postreforma.csv	CSV	Curva logística 37 meses
data/df_radar_multicriterio.csv	CSV	Índice bienestar NNA
data/df_contexto_trata_ballard.csv	CSV	Contexto trata infantil
reporte_estudio_completo.md	Markdown	Reporte documentado
figures/fig1_dashboard_principal.png	PNG	Dashboard 4 subplots
figures/fig2_impacto_nlp_multicriterio.png	PNG	NLP + Radar + Ahorro
figures/fig3_modelo_predictivo_heatmap.png	PNG	Random Forest + Heatmap
figures/fig4_analisis_estadistico.png	PNG	Correlaciones + Boxplots
Cómo ejecutar
bash
pip install pandas numpy matplotlib
python estudio_adopciones_ecuador_completo.py

El script genera automáticamente los 4 PNGs y los 9 CSVs en la carpeta de salida configurada al inicio del archivo (OUTPUT_DIR).

Nota metodológica

Las proyecciones son estimaciones basadas en modelos predictivos (función logística, Random Forest) y datos comparativos regionales; no constituyen cifras oficiales del Estado ecuatoriano.

Licencia

Este proyecto se comparte con fines de análisis y transparencia. Ajusta esta sección según la licencia que quieras aplicar (MIT, CC-BY, etc.).
