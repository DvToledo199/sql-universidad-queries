# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 20 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.41 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.56 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY,id_asignatura,id_curso_escolar, PRIMARY

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor,id_grado, PRIMARY,id_departamento

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.43 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,9 +1,24 @@
 nombre
 Informática
+Informática
+Informática
+Informática
+Informática
+Informática
+Informática
+Informática
+Informática
+Informática
+Informática
+Matemáticas
 Matemáticas
 Economía y Empresa
+Economía y Empresa
+Educación
+Educación
 Educación
 Agronomía
+Química y Física
 Química y Física
 Filología
 Derecho
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_profesor, id_departamento, id_asignatura

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-grau | total
-Grado en Ingeniería Informática (Plan 2015) | 51.00
+1
+1.00
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,2 @@
-grau | tipo | total_creditos
-Grado en Ingeniería Informática (Plan 2015) | básica | 72.00
-Grado en Ingeniería Informática (Plan 2015) | obligatoria | 54.00
-Grado en Ingeniería Informática (Plan 2015) | optativa | 180.00
-Grado en Biotecnología (Plan 2015) | básica | 60.00
-Grado en Biotecnología (Plan 2015) | obligatoria | 120.00
+1
+1.00
```

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,2 @@
-anyo_inicio | total
-2014.00 | 3.00
-2018.00 | 3.00
+1
+1.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,2 @@
-id | nombre | apellido1 | apellido2 | total
-14.00 | Manolo | Hamill | Kozey | 11.00
-3.00 | Zoe | Ramirez | Gea | 10.00
-5.00 | David | Schmidt | Fisher | 0.00
-15.00 | Alejandro | Kohler | Schoen | 0.00
-8.00 | Cristina | Lemke | Rutherford | 0.00
-16.00 | Antonio | Fahey | Considine | 0.00
-10.00 | Esther | Spencer | Lakin | 0.00
-12.00 | Carmen | Streich | Hirthe | 0.00
-17.00 | Guillermo | Ruecker | Upton | 0.00
-18.00 | Micaela | Monahan | Murray | 0.00
-13.00 | Alfredo | Stiedemann | Morissette | 0.00
-20.00 | Francesca | Schowalter | Muller | 0.00
+1
+1.00
```

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 26: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,2 @@
-apellido1 | apellido2 | nombre
-Schmidt | Fisher | David
-Kohler | Schoen | Alejandro
-Lemke | Rutherford | Cristina
-Fahey | Considine | Antonio
-Spencer | Lakin | Esther
-Streich | Hirthe | Carmen
-Ruecker | Upton | Guillermo
-Monahan | Murray | Micaela
-Stiedemann | Morissette | Alfredo
-Schowalter | Muller | Francesca
+1
+1.00
```

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---
