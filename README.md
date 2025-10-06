# [Practica GitHub Flow]

Proyecto de grupo con metodología **GitHub Flow**.

---

## Reglas Clave

* La rama **`main`** **es la versión final y funcional del proyecto.**. 
* **Nunca** trabajar directamente sobre `main`.

---

## Pauta de Trabajo

### 1. Empezar
* **Actualizar `main`**: `git pull`.
* Crear una **rama nueva** para cada tarea.

### 2. Nombres de Ramas (Obligatorio)
* **Formato**: [AÑO][MES][DÍA]-[INICIALES]-[DESCRIPCIÓN-CORTA]
    * *Ejemplo*: `20251006-AT-fix-footer-link`

### 3. Subir e Integrar
* Sube tu rama: `git push`.
* Abre un **Pull Request (PR)** para unir a `main`.

### 4. Fusión (*Merge*)
* **Solo [El lider de grupo]** aprueba y une el PR.
* **Borra** la rama después de la unión.

---

## Comandos Esenciales

### A. Para Empezar
```bash
git checkout main
git pull
git checkout -b 20251006-AT-fix-footer-link