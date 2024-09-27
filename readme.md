# WTFood

### Objetivo

Crear un algoritmo de recomendación de platos saludables basado en reseñas de usuarios, costo de preparación y composición nutricional. Está dirigido a nutricionistas y jóvenes adultos interesados en mejorar su alimentación. Para ello seguiremos la metodología [CRISP-DM](https://blogdatlas.wordpress.com/2020/02/16/4-metodologias-para-proyectos-de-data-science-datlas-research/) para el desarrollo del proyecto.

---

**Fuentes de Datos**:

- [Recipe Reviews and User Feedback Dataset](https://archive.ics.uci.edu/dataset/911/recipe+reviews+and+user+feedback+dataset)

### Diccionario de Datos

| **Variable Name**  | **Type**     | **Description**                                                                 |
|--------------------|--------------|---------------------------------------------------------------------------------|
| `recipe_code`      | Integer      | ID único de la receta                                                           |
| `recipe_name`      | Categorical  | Nombre de la receta                                                             |
| `user_id`          | Categorical  | ID único del usuario que dejó el comentario                                     |
| `user_reputation`  | Integer      | Puntuación del usuario                                                          |
| `thumbs_up`        | Integer      | Votos positivos al comentario                                                   |
| `stars`            | Integer      | Puntuación dada por el usuario (1 a 5)                                          |
| `text`             | Categorical  | Contenido textual del comentario                                                |

---

### Algoritmo de Recomendación

1. **Preparación de Datos**:
   - Limpieza y unificación de los datasets (recetas y reviews).

2. **Modelado**:
   - Recomendaciones basadas en datos nutricionales, tiempo de preparación y reseñas.

---

### Datasets usados

- [Tipos de dietas y valor nutricional](https://www.kaggle.com/datasets/thedevastator/healthy-diet-recipes-a-comprehensive-dataset)
- [Reviews y tiempo de preparación](https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews)

