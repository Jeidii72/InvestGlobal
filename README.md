🌍 InvestIA API de Análisis de Inversión
Invest Global Scout es una solución desarrollada en .NET 8 que permite a inversores y analistas obtener una visión rápida de la estabilidad económica de cualquier país. La plataforma integra datos demográficos en tiempo real con modelos de Inteligencia Artificial para generar recomendaciones estratégicas.
🚀 Características Principales
Consumo de Datos Reales: Conexión directa con la API de RestCountries para obtener población y moneda oficial.
Inteligencia Artificial Integrada: Uso de modelos de lenguaje de Hugging Face (BART Large CNN) para el análisis de riesgo.
Arquitectura Limpia: Implementación de DTOs para una respuesta JSON estructurada y eficiente.
Documentación Interactiva: Swagger configurado para pruebas inmediatas de los endpoints.
🛠️ Stack Tecnológico
Backend: ASP.NET Core Web API (.NET 8)
IA: Hugging Face Inference API
Datos Externos: RestCountries API
Gestión: Trello (Metodología Ágil)
📦 Instalación y Uso
Clona el repositorio:
git clone https://github.com/Jeidii72/InvestGlobal
Abre la solución en Visual Studio 2022.
Ejecuta el proyecto (F5).
Accede a la interfaz de Swagger en: https://localhost:7207/swagger/index.html
📊Ejemplo JSON
{
  "pais": "colombia",
  "datosEconomicos": "Población: 53.057.212 | Moneda: COP",
  "analisisIA": "[{\"summary_text\":\"COP: Analizar estabilidad de inversión para colombia. Datos: 53057212 habitantes y moneda COP. Analiza estabilidades de inversiones para Colombia, aprovechado by COP.\"}]",
  "recomendacion": "Basado en el análisis de IA: Procesado"
}
{
  "pais": "brazil",
  "datosEconomicos": "Población: 213.421.037 | Moneda: BRL",
  "analisisIA": "[{\"summary_text\":\"Analizar estabilidad de inversión para brazil. Datos: 213421037 habitantes y moneda BRL. Analización de inversiones: Analiza estabilidades de invernadores para Brazil.\"}]",
  "recomendacion": "Basado en el análisis de IA: Procesado"
}
{
  "pais": "croatia",
  "datosEconomicos": "Población: 3.866.233 | Moneda: EUR",
  "analisisIA": "[{\"summary_text\":\"Analizar estabilidad de inversión para croatia. Datos: 3866233 habitantes y moneda EUR. Analización de inversiones para Croatia: http://www.cnn.com/2013/01/29/croatia-investment/index.html#storylink=cpy.\"}]",
  "recomendacion": "Basado en el análisis de IA: Procesado"
}
📈 Evolución Futura
Fine-Tuning: Entrenamiento del modelo de IA con datasets financieros específicos.
OpenAI Integration: Migración opcional a GPT-4 para análisis más profundos.
Dashboard Frontend: Creación de una interfaz gráfica en React o Angular.
