# Dashboard Yopiverso - Campaña Laive en Roblox

Dashboard interactivo desarrollado por **Konektor Chile** para el monitoreo integral de la campaña de Laive en el metaverso Yopiverso de Roblox. Esta herramienta proporciona análisis en tiempo real de métricas de engagement, publicidad y retorno de inversión.

**Estado:** ✅ Activo | **Última actualización:** Julio 2025 | **Plataforma:** Roblox

## 🎯 Características Principales

### Métricas de Experiencia
- **Usuarios Activos Diarios**: Seguimiento de la audiencia activa
- **Nuevos Usuarios**: Adquisición diaria de usuarios
- **Tiempo de Sesión**: Duración promedio de interacción
- **Retención Día 1**: Indicador de calidad de experiencia
- **Visitas Totales Acumuladas**: Alcance total de la campaña

### Métricas Publicitarias
- **ROI de Plays**: Plays generados por dólar invertido
- **ROI de Visitas**: Visitas generadas por dólar invertido
- **Costo por Play (CPP)**: Eficiencia de conversión publicitaria
- **Costo por Visita (CPV)**: Eficiencia de adquisición
- **Tráfico Orgánico vs Pagado**: Distribución de fuentes de tráfico

### KPIs de Marca
- **Tiempo Total de Interacción**: Engagement acumulado con la marca
- **Costo por Minuto de Interacción**: Eficiencia de inversión en branding
- **Eficiencia de Conversión**: Porcentaje de clicks que generan plays

## 🚀 Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet para cargar librerías CDN

### Instalación
1. Clona este repositorio:
```bash
git clone https://github.com/konektor-chile/dashboard-yopiverso-laive.git
cd dashboard-yopiverso-laive
```

2. Abre el archivo `index.html` en tu navegador web
3. El dashboard cargará automáticamente los datos desde `data.json`

### Estructura del Proyecto
```
dashboard-yopiverso-laive/
├── index.html          # Dashboard principal
├── data.json           # Datos de métricas actualizables
├── README.md           # Documentación
└── assets/             # Recursos adicionales (si aplica)
```

## 📊 Actualización de Datos

### Formato del Archivo data.json

El dashboard lee los datos desde `data.json` con la siguiente estructura:

```json
{
  "lastUpdate": "2025-07-01",
  "experienceMetrics": [
    {
      "fecha": "2025-07-01",
      "usuariosActivosDiarios": 2510,
      "nuevosUsuarios": 1816,
      "tiempoSesionPromedio": 2.8,
      "retencionDia1": 0.03,
      "visitasTotales": 179700
    }
  ],
  "advertisingMetrics": {
    "totalImpressions": 21664994,
    "totalClicks": 261028,
    "totalPlays": 111643,
    "totalSpent": 7157.99,
    "costPerPlay": 0.064,
    "costPerVisit": 0.0398
  },
  "campaigns": [
    {
      "name": "Nombre de Campaña",
      "campaignId": "unique-id",
      "startDate": "2025-06-01",
      "endDate": "2025-06-30",
      "objective": "Maximize Plays",
      "plays": 12417,
      "spent": 1143.06
    }
  ]
}
```

### Proceso de Actualización

1. **Exportar datos de Roblox Analytics**
2. **Formatear según estructura JSON**
3. **Reemplazar contenido de data.json**
4. **Actualizar campo lastUpdate**
5. **Refrescar dashboard en navegador**

## 🎨 Funcionalidades del Dashboard

### Filtros Temporales
- Selección de rango de fechas personalizado
- Botón "Aplicar" para filtrar métricas
- Botón "Todo el período" para resetear filtros

### Visualizaciones Interactivas
- **Gráficos de líneas**: Tendencias temporales
- **Gráficos de barras**: Comparaciones de campañas
- **Tarjetas KPI**: Métricas destacadas con colores diferenciados
- **Tabla top campañas**: Ranking de rendimiento

### Cálculos Automáticos
El dashboard calcula automáticamente:
- Proporción de tráfico orgánico vs pagado
- ROI publicitario por objetivo de campaña
- Tiempo total de interacción con la marca
- Eficiencia de conversión por tipo de campaña

## 🔧 Personalización

### Colores de Marca
El dashboard utiliza la paleta de colores de Laive:
- **Rojo principal**: #E31E24
- **Gradientes personalizados**: Configurables en CSS
- **Esquema responsive**: Adaptable a dispositivos móviles

### Métricas Adicionales
Para agregar nuevas métricas:
1. Actualizar estructura en `data.json`
2. Añadir elementos HTML en `index.html`
3. Implementar lógica de cálculo en JavaScript

## 📈 Casos de Uso

### Reportes Ejecutivos
- Vista consolidada de ROI por período
- Comparación de eficiencia entre campañas
- Análisis de tendencias de engagement

### Optimización de Campañas
- Identificación de campañas con mejor CPP
- Análisis de tráfico orgánico generado
- Evaluación de retención de usuarios

### Planificación Estratégica
- Proyección de inversión basada en CPV
- Análisis de estacionalidad en métricas
- Benchmarking de objetivos de campaña

## 🛠️ Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Estilos**: Tailwind CSS 2.2.19
- **Gráficos**: Chart.js
- **Iconos**: Font Awesome 6.4.0
- **Responsive Design**: Mobile-first approach

## 📞 Soporte y Contacto

### Desarrollado por Konektor Chile
**Sebastián Wagner** - Key Account Manager  
📧 **Email**: Disponible vía calendario  
📅 **Agendar reunión**: [meetings.hubspot.com/sebastian592](https://meetings.hubspot.com/sebastian592)  
🌐 **Especialización**: Marketing inmersivo para el Cono Sur de LATAM

### Servicios Adicionales
- Implementación de dashboards personalizados
- Integración con APIs de Roblox Analytics
- Consultorías en estrategias de metaverso
- Desarrollo de experiencias inmersivas

## 📝 Licencia y Uso

Este dashboard ha sido desarrollado específicamente para la campaña Yopiverso de Laive. Para adaptaciones o implementaciones similares, contactar a Konektor Chile.

---

**🎮 Transformando la presencia de marcas en el metaverso** | Konektor Chile 2025
