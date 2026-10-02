# Plantilla: propuesta del Proyecto A

---

## 0 · Datos

| |                             |
|---|-----------------------------|
| **Nombre de la app** | Espify                      |
| **Autor/a** | Alfredo Miguel Osorio Arias |
| **Fecha** | 02/10/2026                  |

---

## 1 · La idea en una frase

> Qué hace tu app y para quién, en una sola frase.
>
> Fórmula: «Una app que permite a [quién] hacer [qué] para [para qué].»

Una app que permite a un jugador de cartas TCG hacer listas de cartas para saber su stock

---

## 2 · El problema

> ¿Qué problema resuelve? ¿Cómo se resuelve hoy sin tu app?

No tener que llevar todas las cartas a convenciones o reuniones, sino solo mostrar la lista y ahí ver que se quiere vender/comprar
Hay aplicaciones que hacen algo similar, pero limitan las listas.

---

## 3 · Personas usuarias

> ¿Quién la va a usar? Describe a una persona concreta: edad, soltura con la
> tecnología, cuándo y dónde abre la app, cuánto tiempo le dedica y qué pasa
> si le falla.

Facil para cualquier edad, que debe dedicarle tanto tiempo como cuantas cartas quiera subir a su lista.

---

## 4 · Funcionalidades

### Imprescindibles (sin esto la app no tiene sentido)

| # | Funcionalidad    |
|---|------------------|
| F1 | crear listas     |
| F2 | compartir listas |

### Opcionales (si sobra tiempo)

| # | Funcionalidad |
|---|---------------|
| O1 | |
| O2 | |

---

## 5 · Pantallas

| Pantalla        | Para qué sirve                                             | Se llega desde              |
|-----------------|------------------------------------------------------------|-----------------------------|
| principal       | muestra las diferentes opciones o casos de uso de la app   | (arranque)                  |
| agregar stock   | permite agregar cartas a la lista                          | boton en pantalla principal |
| compartir lista | permite compartir un vinculo a tu para ser vista por otros | boton en pantalla principal |

---

## 6 · Bocetos

> Dibuja las pantallas principales. A mano y fotografiado es válido.
> Pega aquí las imágenes o indica el nombre de los archivos adjuntos.

![pantalla principal.jpg](res/pantalla%20principal.jpg)
![pantalla mis listas.jpg](res/pantalla%20mis%20listas.jpg)
![pantalla listas compartidas conmigo.jpg](res/pantalla%20listas%20compartidas%20conmigo.jpg)

---

## 7 · Qué datos guarda la app

| Tipo de dato    | Campos               | Ejemplo                  |
|-----------------|----------------------|--------------------------|
| carta | nombre, tipo, rareza | pikachu, electrico, raro |

---

## 8 · Encaje con los requisitos del módulo

> Apartado obligatorio: ninguna casilla puede quedar vacía.

| Requisito | Dónde encaja en tu app                                                   | Tema |
|-----------|--------------------------------------------------------------------------|------|
| **Persistencia de datos** — la información sobrevive al cerrar la app | no                                                                       | 4 |
| **Servicio web** — la app consulta datos por internet | si, lo necesita para obtener las imagenes o nombres reales de las cartas | 5 |
| **Sensor o localización** | ninguno                                                                  | 6 |
| **Contenido multimedia** — foto, audio, vídeo o animación | imagenes de las cartas de las listas                                     | 7 |

---

## 9 · Riesgos

| Lo que me preocupa                                    | Plan B                                                                                                                                                 |
|-------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| que las listas no carguen las imagenes desde internet | se generaran imágenes genéricas con bordes simples y texto plano paa simular la carta, solo que no tendrá los bordes especiales o el arte de la carta. |

---

## Antes de entregar

- [ ] La idea cabe en una frase.
- [ ] El público es una persona concreta, no «todo el mundo».
- [ ] Hay **3 o 4** funcionalidades imprescindibles, no diez.
- [ ] Cada funcionalidad imprescindible tiene su pantalla.
- [ ] Hay bocetos de las pantallas principales.
- [ ] **Las cuatro casillas del apartado 8 están rellenas.**
- [ ] Está identificado al menos un riesgo con su plan B.
