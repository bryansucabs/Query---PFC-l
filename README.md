Implementación del detector de objetos Featurized Query R-CNN que combina Faster R-CNN con mecanismos de consulta.

**Featurized Query R-CNN** es un detector de objetos avanzado que fusiona la arquitectura probada de **Faster R-CNN** con innovadores mecanismos de consulta (query) inspirados en DETR.

### 🔍 Problemas que Resuelve

1. **Optimización Compleja**: 
   - Métodos tradicionales requieren decodificadores multi-etapa para optimizar queries aleatorias
   - Nuestro enfoque elimina esta complejidad computacional

2. **Falta de Flexibilidad**:
   - Queries fijas después del entrenamiento limitan la generalización
   - Queries featurizadas se adaptan dinámicamente
     
**Componentes Clave:**
- **Backbone CNN** (ResNet-50/101) - Extracción robusta de características
- **Query Generation Network** - Generación inteligente de consultas
- **RPN Mejorado** - Detección de regiones con contexto enriquecido
- **Detection Head** - Clasificación y refinamiento preciso
