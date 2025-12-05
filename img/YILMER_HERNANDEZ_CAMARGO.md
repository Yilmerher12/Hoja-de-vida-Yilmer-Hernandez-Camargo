# Semana 01 - Introducción al Paradigma Orientado a Objetos

**Estudiante:** Yilmer Hernandez Camargo  
**Ficha:** 3228970A  
**Dominio Asignado:** Consultoría Empresarial "Soluciones Estratégicas"

---

## 📋 Contexto del Dominio

**Tipo de Negocio:** Consultoría Empresarial  
**Nombre Comercial:** Soluciones Estratégicas  
**Ubicación:** Bogotá, World Trade Center  
**Especialidad:** Consultoría en gestión, finanzas, marketing, recursos humanos

### Descripción Breve
Soluciones Estratégicas es una firma de consultoría que brinda servicios de asesoría empresarial a pequeñas, medianas y grandes empresas. Ofrece servicios de planeación estratégica, optimización de procesos, análisis financiero, marketing digital y gestión del talento humano. Cuenta con 15 consultores especializados y atiende a 40 clientes corporativos.

---

## 🎯 Objetivos de la Semana 01

Al finalizar esta semana, deberás ser capaz de:

1. Identificar objetos del mundo real en el contexto de una consultoría empresarial
2. Comprender las diferencias entre programación estructurada y POO
3. Reconocer los conceptos fundamentales: clase, objeto, atributo, método
4. Crear tu primera clase simple en Java aplicada al dominio

---

## 📝 Actividades Obligatorias

### Actividad 1: Identificación de Objetos (Ejercicio 01)

**Instrucciones:**
- Lee el material teórico de la semana sobre conceptos fundamentales de POO
- Identifica **5 objetos principales** que existen en una consultoría empresarial
- Para cada objeto, describe:
  - ¿Qué es? (definición)
  - ¿Qué características tiene? (atributos)
  - ¿Qué puede hacer? (comportamientos/métodos)

**Ejemplo:**
```
Objeto: Proyecto de Consultoría
- ¿Qué es?: Un servicio contratado por un cliente para resolver una necesidad empresarial
- Características: código, cliente, área, consultor asignado, fecha inicio, duración, presupuesto
- Comportamientos: crear proyecto, asignar consultor, ejecutar, entregar informe, facturar
```

**Entregable:** Documento con la identificación de 5 objetos del dominio de la consultoría empresarial.

---

### Actividad 2: Comparación de Paradigmas (Ejercicio 02)

**Instrucciones:**
- Investiga las diferencias entre programación estructurada y POO
- Escribe un ejemplo conceptual de cómo se manejaría la información de un proyecto en:
  1. **Programación estructurada** (usando variables sueltas y funciones)
  2. **Programación orientada a objetos** (usando una clase)

**Entregable:** Documento comparativo con ejemplos explicados.

---

### Actividad 3: Primera Clase Simple (Ejercicio 03)

**Instrucciones:**
Crea tu primera clase en Java llamada `ConsultingProject` (Proyecto de Consultoría) con:
- **3 atributos** (ej: `projectCode`, `area`, `duration`)
- **1 constructor** que inicialice los atributos
- **1 método** que muestre la información del proyecto

**Código de ejemplo:**

```java
public class ConsultingProject {
    // Atributos
    String projectCode;
    String area;
    int duration;
    
    // Constructor
    public ConsultingProject(String projectCode, String area, int duration) {
        this.projectCode = projectCode;
        this.area = area;
        this.duration = duration;
    }
    
    // Método para mostrar información
    public void showInfo() {
        System.out.println("Código: " + projectCode);
        System.out.println("Área: " + area);
        System.out.println("Duración: " + duration + " semanas");
    }
}
```

**Instrucciones adicionales:**
1. Crea una clase `Main` con el método `main`
2. Instancia **3 objetos diferentes** de tipo `ConsultingProject`
3. Llama al método `showInfo()` para cada objeto

**Entregable:** Archivo `ConsultingProject.java` y `Main.java` funcionando correctamente.

---

### Actividad 4: Múltiples Objetos (Ejercicio 04)

**Instrucciones:**
Amplía el ejercicio anterior:
- Crea al menos **5 objetos** de tipo `ConsultingProject` con datos diferentes
- Cada proyecto debe tener información coherente con una consultoría empresarial real
- Muestra la información de todos los proyectos

**Ejemplo de datos:**
- CONS-001, Planeación Estratégica, 12
- CONS-002, Optimización de Procesos, 8
- CONS-003, Análisis Financiero, 6
- CONS-004, Marketing Digital, 10
- CONS-005, Gestión del Talento, 14

**Entregable:** Código Java con 5 instancias de `ConsultingProject` y su salida en consola.

---

## 🎓 Criterios de Evaluación

| Criterio | Peso | Descripción |
|----------|------|-------------|
| **Identificación de objetos** | 25% | Objetos identificados son relevantes al dominio de la consultoría empresarial |
| **Comprensión conceptual** | 25% | Demuestra entender diferencias entre paradigmas |
| **Implementación de clase** | 30% | Clase `ConsultingProject` implementada correctamente con atributos, constructor y método |
| **Instanciación de objetos** | 20% | Crea múltiples objetos con datos coherentes |

---

## 📚 Recursos de Apoyo

### Material Teórico (Carpeta `1-teoria/`)
- `01-historia-evolucion-poo.md`
- `02-paradigmas-programacion.md`
- `03-conceptos-fundamentales-poo.md`
- `04-primer-programa-poo.md`

### Ejercicios Guiados (Carpeta `2-practica/`)
- `ejercicio-01-comparacion-paradigmas/`
- `ejercicio-02-primera-clase/`
- `ejercicio-03-multiples-objetos/`
- `ejercicio-04-modelado-mundo-real/`

### Glosario
Revisa el archivo `3-recursos/glosario.md` para términos clave de esta semana.

---

## 💡 Consejos

1. **No te compliques:** Esta semana es sobre conceptos básicos, no sobre código complejo
2. **Piensa en objetos reales:** Visualiza cómo funciona una consultoría empresarial real
3. **Pregunta:** Si tienes dudas sobre el dominio o los conceptos, consulta con el instructor
4. **Compila y prueba:** Asegúrate de que tu código compile antes de entregar

---

## 📅 Fecha de Entrega

**Entrega:** Según calendario definido por el instructor  
**Formato:** Código fuente (.java) y documentos en formato Markdown o PDF

---

**Nota Importante:** Este es tu dominio personal para todo el bootcamp. Todas las actividades futuras seguirán en el contexto de la consultoría empresarial Soluciones Estratégicas. No compartas tu código directamente con otros estudiantes, ya que cada uno tiene un dominio diferente.
