<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Control de reportes obligatorios</title>
<style>
:root{--azul:#12345b;--verde:#2f8f57;--borde:#d7e0e8;--fondo:#f4f7fa;--texto:#17283a}
*{box-sizing:border-box}
body{margin:0;padding:22px;font-family:Arial,Helvetica,sans-serif;background:var(--fondo);color:var(--texto)}
.contenedor{max-width:1250px;margin:0 auto}
.reporte{background:#fff;border:1px solid var(--borde);border-radius:12px;padding:20px;margin-bottom:18px;box-shadow:0 1px 2px #12345b0a}
.reporte-cabecera{display:flex;align-items:flex-start;justify-content:space-between;gap:16px;margin-bottom:14px}
.nombre{font-size:19px;font-weight:700;color:var(--azul);margin:0 0 6px}
.descripcion{font-size:13px;color:#667788;margin:0}
.plazo{display:inline-block;background:#edf7f0;color:#236d41;border-radius:7px;padding:8px 10px;font-size:13px;font-weight:700;white-space:normal;text-align:center}
.controles{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:9px}
.check{display:flex;align-items:center;gap:9px;padding:12px;background:#f8fafc;border:1px solid var(--borde);border-radius:8px;cursor:pointer;min-height:46px;font-size:14px}
.check:has(input:checked){background:#edf7f0;border-color:#91c8a3;color:#205f39}
.check input{width:19px;height:19px;accent-color:var(--verde);flex-shrink:0;cursor:pointer}
.vigilancia{border-left:7px solid #7440a8}.mental{border-left:7px solid #159aa0}.vacunacion{border-left:7px solid #1976d2}.tb{border-left:7px solid #f07819}.bai{border-left:7px solid #63a72f}.revcom{border-left:7px solid #df3f83}
.pie{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap;color:#667788;font-size:12px;padding:2px 4px 12px}
.estado{font-weight:700;color:var(--verde)}
.boton{border:1px solid var(--borde);background:white;color:var(--azul);padding:8px 12px;border-radius:7px;cursor:pointer;font-weight:700}
.boton:hover{background:#edf2f7}
@media(max-width:600px){body{padding:10px}.reporte{padding:14px}.reporte-cabecera{display:block}.plazo{margin-top:10px}.nombre{font-size:17px}}
</style>
</head>
<body>
<main class="contenedor" aria-label="Lista de chequeo de reportes obligatorios">
  <section class="reporte vigilancia">
    <div class="reporte-cabecera"><div><h2 class="nombre">🟣 Notificación al Sistema de Vigilancia en Salud Pública (SIVIGILA)</h2><p class="descripcion">Reporte semanal.</p></div><span class="plazo">Todos los lunes · antes de las 12:00 p. m.</span></div>
    <div class="controles">
      <label class="check"><input type="checkbox" data-key="sivigila-2026-10-05"> 05 OCT</label><label class="check"><input type="checkbox" data-key="sivigila-2026-10-12"> 12 OCT</label><label class="check"><input type="checkbox" data-key="sivigila-2026-10-19"> 19 OCT</label><label class="check"><input type="checkbox" data-key="sivigila-2026-10-26"> 26 OCT</label>
      <label class="check"><input type="checkbox" data-key="sivigila-2026-11-02"> 02 NOV</label><label class="check"><input type="checkbox" data-key="sivigila-2026-11-09"> 09 NOV</label><label class="check"><input type="checkbox" data-key="sivigila-2026-11-16"> 16 NOV</label><label class="check"><input type="checkbox" data-key="sivigila-2026-11-23"> 23 NOV</label><label class="check"><input type="checkbox" data-key="sivigila-2026-11-30"> 30 NOV</label>
      <label class="check"><input type="checkbox" data-key="sivigila-2026-12-07"> 07 DIC</label><label class="check"><input type="checkbox" data-key="sivigila-2026-12-14"> 14 DIC</label><label class="check"><input type="checkbox" data-key="sivigila-2026-12-21"> 21 DIC</label><label class="check"><input type="checkbox" data-key="sivigila-2026-12-28"> 28 DIC</label>
    </div>
  </section>

  <section class="reporte mental">
    <div class="reporte-cabecera"><div><h2 class="nombre">🧠 Notificación de acciones del Plan de Acción en Salud Mental</h2><p class="descripcion">Reporte semanal.</p></div><span class="plazo">Todos los lunes · antes de las 4:00 p. m.</span></div>
    <div class="controles">
      <label class="check"><input type="checkbox" data-key="mental-2026-10-05"> 05 OCT</label><label class="check"><input type="checkbox" data-key="mental-2026-10-12"> 12 OCT</label><label class="check"><input type="checkbox" data-key="mental-2026-10-19"> 19 OCT</label><label class="check"><input type="checkbox" data-key="mental-2026-10-26"> 26 OCT</label>
      <label class="check"><input type="checkbox" data-key="mental-2026-11-02"> 02 NOV</label><label class="check"><input type="checkbox" data-key="mental-2026-11-09"> 09 NOV</label><label class="check"><input type="checkbox" data-key="mental-2026-11-16"> 16 NOV</label><label class="check"><input type="checkbox" data-key="mental-2026-11-23"> 23 NOV</label><label class="check"><input type="checkbox" data-key="mental-2026-11-30"> 30 NOV</label>
      <label class="check"><input type="checkbox" data-key="mental-2026-12-07"> 07 DIC</label><label class="check"><input type="checkbox" data-key="mental-2026-12-14"> 14 DIC</label><label class="check"><input type="checkbox" data-key="mental-2026-12-21"> 21 DIC</label><label class="check"><input type="checkbox" data-key="mental-2026-12-28"> 28 DIC</label>
    </div>
  </section>

  <section class="reporte vacunacion">
    <div class="reporte-cabecera"><div><h2 class="nombre">💉 Informe mensual de vacunación</h2><p class="descripcion">Consolidado mensual.</p></div><span class="plazo">Día 30 de cada mes</span></div>
    <div class="controles"><label class="check"><input type="checkbox" data-key="vacunacion-2026-10-30"> 30 OCT</label><label class="check"><input type="checkbox" data-key="vacunacion-2026-11-30"> 30 NOV</label><label class="check"><input type="checkbox" data-key="vacunacion-2026-12-30"> 30 DIC</label></div>
  </section>

  <section class="reporte tb">
    <div class="reporte-cabecera"><div><h2 class="nombre">🫁 Informe de tuberculosis</h2><p class="descripcion">Consolidado mensual.</p></div><span class="plazo">Antes del día 10 de cada mes</span></div>
    <div class="controles"><label class="check"><input type="checkbox" data-key="tuberculosis-2026-10"> OCTUBRE</label><label class="check"><input type="checkbox" data-key="tuberculosis-2026-11"> NOVIEMBRE</label><label class="check"><input type="checkbox" data-key="tuberculosis-2026-12"> DICIEMBRE</label></div>
  </section>

  <section class="reporte bai">
    <div class="reporte-cabecera"><div><h2 class="nombre">🔎 Búsqueda Activa Institucional (BAI)</h2><p class="descripcion">Consolidado mensual.</p></div><span class="plazo">Antes del día 15 de cada mes</span></div>
    <div class="controles"><label class="check"><input type="checkbox" data-key="bai-2026-10"> OCTUBRE</label><label class="check"><input type="checkbox" data-key="bai-2026-11"> NOVIEMBRE</label><label class="check"><input type="checkbox" data-key="bai-2026-12"> DICIEMBRE</label></div>
  </section>

  <section class="reporte revcom">
    <div class="reporte-cabecera"><div><h2 class="nombre">🌸 REVCOM</h2><p class="descripcion">Vigilancia epidemiológica basada en comunidad.</p></div><span class="plazo">Antes de las 12:00 p. m.</span></div>
    <div class="controles"><label class="check"><input type="checkbox" data-key="revcom-2026-10"> OCTUBRE</label><label class="check"><input type="checkbox" data-key="revcom-2026-11"> NOVIEMBRE</label><label class="check"><input type="checkbox" data-key="revcom-2026-12"> DICIEMBRE</label></div>
  </section>

  <div class="pie"><span class="estado" id="estado">Los cambios se guardan automáticamente en este navegador.</span><button type="button" class="boton" id="reiniciar">Desmarcar todas las casillas</button></div>
</main>
<script>
(function(){
  const checks = Array.from(document.querySelectorAll('input[type="checkbox"][data-key]'));
  const estado = document.getElementById('estado');
  const prefijo = 'control-reportes-salud-cordoba-2026:';
  function cargar(){
    checks.forEach(function(check){
      try { check.checked = localStorage.getItem(prefijo + check.dataset.key) === '1'; }
      catch(e) { estado.textContent = 'El navegador bloqueó el almacenamiento local; los cambios podrían no conservarse.'; }
    });
  }
  checks.forEach(function(check){
    check.addEventListener('change', function(){
      try {
        localStorage.setItem(prefijo + check.dataset.key, check.checked ? '1' : '0');
        estado.textContent = 'Cambios guardados automáticamente.';
      } catch(e) {
        estado.textContent = 'No se pudo guardar. Abre el archivo en un navegador con almacenamiento habilitado.';
      }
    });
  });
  document.getElementById('reiniciar').addEventListener('click', function(){
    if(!window.confirm('¿Deseas desmarcar todas las casillas guardadas?')) return;
    checks.forEach(function(check){
      check.checked = false;
      try { localStorage.setItem(prefijo + check.dataset.key, '0'); } catch(e) {}
    });
    estado.textContent = 'Todas las casillas quedaron desmarcadas.';
  });
  cargar();
})();
</script>
</body>
</html>

