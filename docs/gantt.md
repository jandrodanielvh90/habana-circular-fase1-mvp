# Diagrama Gantt - Habana Circular

## Visión general

Este documento contiene el cronograma base del proyecto para la Fase 1 del MVP Piloto Digital.

```mermaid
gantt
    title Habana Circular - Fase 1 MVP Piloto Digital (4 Semanas)
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

    section Planificación
    Definición de reglas y materiales :done, 2026-10-12, 7d
    Diseño UX/UI y registro :active, 2026-10-19, 7d

    section Desarrollo Core
    Arquitectura y Base de Datos :2026-10-19, 14d
    Motor de Puntos (Base*kg + Bonus - Penal) :2026-10-19, 14d
    Desarrollo MVP APK :2026-10-26, 14d

    section Piloto y Cierre
    Módulo Educativo (Continuo) :2026-10-12, 28d
    Pruebas QA y 5 Nodos :2026-11-02, 7d
    Documentación y Entrega JICA :2026-11-02, 7d

    section Hitos
    Kickoff Técnico :milestone, 2026-10-12, 0d
    Build Cerrado (APK) :milestone, 2026-10-30, 0d
    Inicio Piloto :milestone, 2026-11-02, 0d
    Reporte Final JICA :milestone, 2026-11-08, 0d
```

## Observaciones
- El proyecto tiene una duración estimada de 4 semanas.
- La fase core está concentrada entre el 19 de octubre y el 2 de noviembre.
- El piloto y cierre contemplan pruebas, validación y documentación.

## Riesgos a monitorear
- Retrasos en definición de reglas operativas
- Ajustes del motor de puntos durante QA
- Dependencias de materiales y nodos para validación
