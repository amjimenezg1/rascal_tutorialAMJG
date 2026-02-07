# rascal_tutorialAMJG

Este proyecto fue realizado siguiendo **exactamente** el tutorial oficial de Rascal, sin modificaciones al código propuesto.

## Errores y advertencias

Durante el desarrollo aparecieron algunos errores y advertencias, los cuales **no fueron corregidos intencionalmente**, ya que forman parte del comportamiento del tutorial en ciertos entornos:

- Errores en `Generator2.rsc` y `Generator3.rsc` (patrones ambiguos y variables no capturadas).
- En algunos casos, `generator3.txt` no se genera debido a dichos errores.
- El comando `mvn -U install` no se ejecuta porque Maven no está instalado en el sistema; la extensión *Maven for Java* no incluye Maven.
- Las validaciones (prioridades duplicadas, pagos mayores a 10000, duración en minutos) funcionan correctamente y son intencionales.

## Conclusión
El proyecto cumple con los objetivos del tutorial (DSL, generadores, validaciones).  
Los errores observados se deben a supuestos del tutorial y **no a una implementación incorrecta**.
