<!DOCTYPE html>
<html lang="es">

<head>

<meta charset="UTF-8">

<meta name="viewport"
content="width=device-width, initial-scale=1.0">

<title>
Reportes Obligatorios - Plan Local de Salud Córdoba Quindío
</title>

<style>

body{
    margin:0;
    padding:25px;
    font-family:Arial,Helvetica,sans-serif;
    background:#f4f7fa;
    color:#17283a;
}

.contenedor{
    max-width:1400px;
    margin:auto;
}


/* ENCABEZADO */

.encabezado{
    background:white;
    border:2px solid #d8e2eb;
    border-radius:18px;
    padding:30px;
    margin-bottom:25px;
    text-align:center;
}

.encabezado h1{
    margin:0;
    font-size:34px;
    color:#12345b;
}

.encabezado h2{
    margin:8px 0;
    color:#2f8f57;
    font-size:24px;
}

.encabezado p{
    color:#667788;
    font-size:16px;
}


/* TABLA */

.tabla{
    width:100%;
    border-collapse:separate;
    border-spacing:8px;
}


/* ENCABEZADOS */

.tabla th{

    background:#12345b;

    color:white;

    padding:16px;

    font-size:16px;

    text-align:center;

    border-radius:8px;

}


/* CELDAS */

.tabla td{

    background:white;

    padding:18px;

    vertical-align:top;

    border:1px solid #d7e0e8;

}


/* NOMBRE DEL REPORTE */

.reporte{

    font-weight:bold;

    font-size:17px;

    color:#12345b;

}


.descripcion{

    margin-top:8px;

    font-size:13px;

    color:#667788;

}


/* PLAZO */

.plazo{

    text-align:center;

    font-weight:bold;

    color:#2f8f57;

    font-size:17px;

}


/* CONTROL */

.control{

    display:grid;

    grid-template-columns:
    repeat(4,1fr);

    gap:8px;

}


/* CHECKBOX */

.check{

    display:flex;

    align-items:center;

    gap:7px;

    padding:10px;

    background:#f8fafc;

    border:1px solid #d7e0e8;

    border-radius:8px;

    font-size:13px;

    cursor:pointer;

}

.check input{

    width:18px;

    height:18px;

}


/* COLORES */

.vigilancia{
    border-left:7px solid #7440a8;
}

.mental{
    border-left:7px solid #159aa0;
}

.vacunacion{
    border-left:7px solid #1976d2;
}

.tb{
    border-left:7px solid #f07819;
}

.bai{
    border-left:7px solid #63a72f;
}

.revcom{
    border-left:7px solid #df3f83;
}


/* CALENDARIO */

.titulo{

    margin-top:35px;

    margin-bottom:15px;

    color:#12345b;

    font-size:25px;

}


.mes{

    background:white;

    border:1px solid #d8e2eb;

    border-radius:12px;

    padding:20px;

    margin-bottom:15px;

}


.mes h3{

    color:#12345b;

    margin-top:0;

}


.fechas{

    display:flex;

    gap:15px;

}


.fecha{

    flex:1;

    background:#f7fafc;

    border-left:6px solid #2f8f57;

    padding:15px;

    border-radius:7px;

}


/* RESPONSIVE */

@media(max-width:900px){

    .control{

        grid-template-columns:
        repeat(2,1fr);

    }

}


@media(max-width:600px){

    body{

        padding:10px;

    }

    .tabla{

        font-size:13px;

    }

    .control{

        grid-template-columns:1fr;

    }

    .fechas{

        flex-direction:column;

    }

}

</style>

</head>


<body>


<div class="contenedor">


<!-- ENCABEZADO -->

<div class="encabezado">

<h1>
REPORTES OBLIGATORIOS
</h1>

<h2>
PLAN LOCAL DE SALUD
</h2>

<h2>
CÓRDOBA – QUINDÍO
</h2>

<p>
<strong>
CONTROL DE REPORTES · OCTUBRE – DICIEMBRE 2026
</strong>
</p>

<p>
Marca ✓ cada vez que el reporte haya sido realizado.
</p>

</div>


<!-- TABLA -->

<table class="tabla">


<thead>

<tr>

<th style="width:35%;">
REPORTE
</th>

<th style="width:18%;">
PLAZO
</th>

<th style="width:47%;">
CONTROL
</th>

</tr>

</thead>


<tbody>


<!-- ================= SIVIGILA ================= -->

<tr>

<td class="vigilancia">

<div class="reporte">

🟣 Notificación al Sistema de Vigilancia en Salud Pública

</div>

<div class="descripcion">

Reporte semanal.

</div>

</td>


<td>

<div class="plazo">

TODOS LOS LUNES

<br><br>

<span style="color:#17283a;font-size:14px;">

Antes de las

<strong>
12:00 p. m.
</strong>

</span>

</div>

</td>


<td>

<div class="control">


<label class="check">
<input type="checkbox">
05 OCT
</label>


<label class="check">
<input type="checkbox">
12 OCT
</label>


<label class="check">
<input type="checkbox">
19 OCT
</label>


<label class="check">
<input type="checkbox">
26 OCT
</label>


<label class="check">
<input type="checkbox">
02 NOV
</label>


<label class="check">
<input type="checkbox">
09 NOV
</label>


<label class="check">
<input type="checkbox">
16 NOV
</label>


<label class="check">
<input type="checkbox">
23 NOV
</label>


<label class="check">
<input type="checkbox">
30 NOV
</label>


<label class="check">
<input type="checkbox">
07 DIC
</label>


<label class="check">
<input type="checkbox">
14 DIC
</label>


<label class="check">
<input type="checkbox">
21 DIC
</label>


<label class="check">
<input type="checkbox">
28 DIC
</label>


</div>

</td>

</tr>


<!-- ================= SALUD MENTAL ================= -->

<tr>

<td class="mental">

<div class="reporte">

🧠 Notificación de acciones del Plan de Acción en Salud Mental

</div>

<div class="descripcion">

Reporte semanal.

</div>

</td>


<td>

<div class="plazo">

TODOS LOS LUNES

<br><br>

<span style="color:#17283a;font-size:14px;">

Antes de las

<strong>
4:00 p. m.
</strong>

</span>

</div>

</td>


<td>

<div class="control">


<label class="check">
<input type="checkbox">
05 OCT
</label>

<label class="check">
<input type="checkbox">
12 OCT
</label>

<label class="check">
<input type="checkbox">
19 OCT
</label>

<label class="check">
<input type="checkbox">
26 OCT
</label>

<label class="check">
<input type="checkbox">
02 NOV
</label>

<label class="check">
<input type="checkbox">
09 NOV
</label>

<label class="check">
<input type="checkbox">
16 NOV
</label>

<label class="check">
<input type="checkbox">
23 NOV
</label>

<label class="check">
<input type="checkbox">
30 NOV
</label>

<label class="check">
<input type="checkbox">
07 DIC
</label>

<label class="check">
<input type="checkbox">
14 DIC
</label>

<label class="check">
<input type="checkbox">
21 DIC
</label>

<label class="check">
<input type="checkbox">
28 DIC
</label>


</div>

</td>

</tr>


<!-- ================= VACUNACION ================= -->

<tr>

<td class="vacunacion">

<div class="reporte">

💉 Informe mensual de vacunación

</div>

<div class="descripcion">

Consolidado mensual.

</div>

</td>


<td>

<div class="plazo">

DÍA 30

<br><br>

<span style="color:#17283a;font-size:14px;">

De cada mes.

</span>

</div>

</td>


<td>

<div class="control">


<label class="check">

<input type="checkbox">

30 OCT

</label>


<label class="check">

<input type="checkbox">

30 NOV

</label>


<label class="check">

<input type="checkbox">

30 DIC

</label>


</div>

</td>

</tr>


<!-- ================= TUBERCULOSIS ================= -->

<tr>

<td class="tb">

<div class="reporte">

🫁 Informe de tuberculosis

</div>

<div class="descripcion">

Consolidado mensual.

</div>

</td>


<td>

<div class="plazo">

ANTES DEL 10

<br><br>

<span style="color:#17283a;font-size:14px;">

De cada mes.

</span>

</div>

</td>


<td>

<div class="control">


<label class="check">

<input type="checkbox">

10 OCT

</label>


<label class="check">

<input type="checkbox">

10 NOV

</label>


<label class="check">

<input type="checkbox">

10 DIC

</label>


</div>

</td>

</tr>


<!-- ================= BAI ================= -->

<tr>

<td class="bai">

<div class="reporte">

🔎 Búsqueda Activa Institucional – BAI

</div>

<div class="descripcion">

Consolidado mensual.

</div>

</td>


<td>

<div class="plazo">

ANTES DEL 10

<br><br>

<span style="color:#17283a;font-size:14px;">

De cada mes.

</span>

</div>

</td>


<td>

<div class="control">


<label class="check">

<input type="checkbox">

10 OCT

</label>


<label class="check">

<input type="checkbox">

10 NOV

</label>


<label class="check">

<input type="checkbox">

10 DIC

</label>


</div>

</td>

</tr>


<!-- ================= REVCOM ================= -->

<tr>

<td class="revcom">

<div class="reporte">

🌸 REVCOM

</div>

<div class="descripcion">

Vigilancia epidemiológica basada en comunidad.

</div>

</td>


<td>

<div class="plazo">

ANTES DE LAS

<br>

12:00 p. m.

</div>

</td>


<td>

<div class="control">


<label class="check">

<input type="checkbox">

OCTUBRE

</label>


<label class="check">

<input type="checkbox">

NOVIEMBRE

</label>


<label class="check">

<input type="checkbox">

DICIEMBRE

</label>


</div>

</td>

</tr>


</tbody>

</table>


<!-- ================= CALENDARIO ================= -->

<div class="titulo">

📅 CALENDARIO DE CONTROL

</div>


<div class="mes">

<h3>
OCTUBRE 2026
</h3>

<div class="fechas">

<div class="fecha">

<strong>
TODOS LOS LUNES
</strong>

<br><br>

SIVIGILA:
12:00 p. m.

<br>

Salud mental:
4:00 p. m.

</div>


<div class="fecha">

<strong>
ANTES DEL 10
</strong>

<br><br>

Tuberculosis

<br>

BAI

</div>


<div class="fecha">

<strong>
30 DE OCTUBRE
</strong>

<br><br>

Informe mensual de vacunación.

</div>

</div>

</div>


<div class="mes">

<h3>
NOVIEMBRE 2026
</h3>

<div class="fechas">

<div class="fecha">

<strong>
TODOS LOS LUNES
</strong>

<br><br>

SIVIGILA:
12:00 p. m.

<br>

Salud mental:
4:00 p. m.

</div>


<div class="fecha">

<strong>
ANTES DEL 10
</strong>

<br><br>

Tuberculosis

<br>

BAI

</div>


<div class="fecha">

<strong>
30 DE NOVIEMBRE
</strong>

<br><br>

Informe mensual de vacunación.

</div>

</div>

</div>


<div class="mes">

<h3>
DICIEMBRE 2026
</h3>

<div class="fechas">

<div class="fecha">

<strong>
TODOS LOS LUNES
</strong>

<br><br>

SIVIGILA:
12:00 p. m.

<br>

Salud mental:
4:00 p. m.

</div>


<div class="fecha">

<strong>
ANTES DEL 10
</strong>

<br><br>

Tuberculosis

<br>

BAI

</div>


<div class="fecha">

<strong>
30 DE DICIEMBRE
</strong>

<br><br>

Informe mensual de vacunación.

</div>

</div>

</div>


</div>

</body>

</html>