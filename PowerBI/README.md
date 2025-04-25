# 📊 Dashboard de Gestión de Reclamos

### 🔗 [Ver reporte en Power BI](https://bit.ly/reclamosView)

---

## 🧩 Problemática

El área de obras públicas del municipio gestionaba los reclamos ciudadanos de forma manual, anotándolos en cuadernos o en hojas de Excel individuales. Esto ocasionaba:
- Pérdida de historial y dificultad para acceder a reclamos antiguos.
- Imposibilidad de consolidar la información entre zonas.
- Falta de análisis para priorizar tareas según urgencia o frecuencia.
- Tiempo excesivo para responder consultas o generar reportes.

No existía un sistema centralizado ni visual que permitiera entender la evolución y distribución geográfica de los reclamos.

---

## 🎯 Solución implementada

Para resolver este problema, diseñé una solución compuesta por:

1. **Un registro centralizado en SharePoint Online**
   - Se creó una lista con campos normalizados: tipo de reclamo, fecha, dirección, estado, etc.
   - Se conectó con Power Apps para cargar los reclamos desde cualquier dispositivo.

2. **Aplicación en Power Apps**
   - Permite registrar los reclamos directamente en campo o desde oficina.
   - Cada dato queda almacenado automáticamente en SharePoint, sin depender de Excel ni papel.

3. **Dashboard en Power BI conectado a SharePoint**
   - Lectura directa de los datos desde la lista.
   - Visualización dinámica e interactiva con filtros por zona, estado, tipo de reclamo y fechas.
   - Se incorporó geolocalización con mapas para detectar zonas más afectadas.
   - Dashboard accesible mediante un link público o institucional.

---

## 📌 Funcionalidades del dashboard

- **Total de reclamos históricos**
- **Reclamos por localidad (gráfico de dona)**
- **Tipos de reclamos más frecuentes (barra horizontal)**
- **Línea de tiempo de evolución anual**
- **Filtro de zona, derivación y estado de trámite**
- **Geolocalización de reclamos con burbujas por cantidad**
- **Detalle específico por tipo de reclamo (ej. sumidero mantenimiento)**

---

## ✅ Impacto obtenido

- Reducción del tiempo de búsqueda de información de días a segundos.
- Identificación rápida de zonas críticas con mayor número de reclamos.
- Mejora en la asignación de recursos y priorización de obras públicas.
- Acceso web inmediato para supervisores, sin necesidad de pedir reportes manuales.
- Conservación del historial completo y trazabilidad de los reclamos.

