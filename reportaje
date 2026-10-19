<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Entre aulas y sueños · La vida universitaria en la UNA Puno</title>
<meta name="description" content="Reportaje digital estudiantil sobre la vida universitaria en la Universidad Nacional del Altiplano de Puno.">
<style>
:root{
  --granate:#7a1f2b; --granate-osc:#561520; --granate-cl:#f6e9eb;
  --gris:#4a4a4f; --gris-cl:#f1f1f3; --gris-med:#d9d9de;
  --blanco:#fff; --ocre:#c58b3a; --lago:#2f6f7e;
  --radio:16px; --sombra:0 6px 20px rgba(60,20,30,.10);
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font-family:"Segoe UI",Roboto,Helvetica,Arial,sans-serif;color:#26262a;background:var(--gris-cl);line-height:1.65;font-size:17px}
h1,h2,h3{font-family:Georgia,"Times New Roman",serif;line-height:1.2;color:var(--granate-osc);margin:0 0 .5em}
h2{font-size:clamp(1.6rem,3.5vw,2.2rem)}
h3{font-size:1.2rem}
p{margin:0 0 1em}
a{color:var(--granate)}
.wrap{max-width:1120px;margin:0 auto;padding:0 18px}

/* Aviso académico */
.aviso{background:var(--granate-osc);color:#fff;font-size:.85rem;text-align:center;padding:8px 14px}

/* Navegación */
nav{position:sticky;top:0;z-index:50;background:rgba(255,255,255,.96);backdrop-filter:blur(6px);border-bottom:1px solid var(--gris-med)}
nav .wrap{display:flex;align-items:center;gap:6px;overflow-x:auto;padding-top:8px;padding-bottom:8px;scrollbar-width:thin}
nav a{flex:0 0 auto;text-decoration:none;color:var(--gris);font-size:.88rem;font-weight:600;padding:7px 12px;border-radius:99px;white-space:nowrap}
nav a:hover{background:var(--granate-cl);color:var(--granate)}
nav a.activo{background:var(--granate);color:#fff}

/* Portada */
.portada{background:linear-gradient(135deg,var(--granate-osc),var(--granate) 60%,#9b3a47);color:#fff;padding:48px 0 56px;position:relative;overflow:hidden}
.portada::after{content:"";position:absolute;inset:auto 0 0 0;height:70px;background:
 linear-gradient(135deg,transparent 33%,rgba(255,255,255,.08) 34% 66%,transparent 67%) 0 0/60px 70px repeat-x;pointer-events:none}
.portada .grid{display:grid;grid-template-columns:1.1fr .9fr;gap:30px;align-items:center}
.etiqueta{display:inline-block;background:rgba(255,255,255,.16);border:1px solid rgba(255,255,255,.35);padding:4px 12px;border-radius:99px;font-size:.78rem;letter-spacing:.06em;text-transform:uppercase;margin-bottom:16px}
.portada h1{color:#fff;font-size:clamp(2rem,5vw,3.3rem)}
.portada .sub{font-size:1.15rem;opacity:.95;margin-bottom:1.2em}
.portada .intro{opacity:.92;max-width:58ch}
.btn{display:inline-block;cursor:pointer;border:0;border-radius:99px;padding:11px 22px;font:inherit;font-weight:700;font-size:.95rem;text-decoration:none;transition:.15s}
.btn-claro{background:#fff;color:var(--granate)}
.btn-claro:hover{background:var(--granate-cl)}
.btn-gr{background:var(--granate);color:#fff}
.btn-gr:hover{background:var(--granate-osc)}
.btn-gris{background:var(--gris-cl);color:var(--gris);border:1px solid var(--gris-med)}
.btn-gris:hover{background:var(--gris-med)}
.btn:focus-visible,input:focus-visible,select:focus-visible,textarea:focus-visible,a:focus-visible{outline:3px solid var(--ocre);outline-offset:2px}

/* Slot de imagen */
.foto{position:relative;border-radius:var(--radio);overflow:hidden;background:var(--gris-cl);border:2px dashed var(--gris-med);display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;color:var(--gris);min-height:220px}
.foto img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.foto .vacio{padding:18px;font-size:.9rem;position:relative;z-index:1}
.foto .vacio b{display:block;font-size:1rem;margin-bottom:4px}
.foto.tiene{border-style:solid;border-color:transparent}
.foto.tiene .vacio{display:none}
.portada .foto{min-height:330px;background:rgba(255,255,255,.1);border-color:rgba(255,255,255,.45);color:#fff}
.carga{display:inline-block;margin-top:8px}
.carga input{display:none}
.carga span{cursor:pointer;display:inline-block;background:var(--granate);color:#fff;padding:7px 14px;border-radius:99px;font-size:.82rem;font-weight:600}
.portada .carga span{background:#fff;color:var(--granate)}
.pie{font-size:.82rem;color:var(--gris);margin-top:8px}
.portada .pie{color:rgba(255,255,255,.85)}
.pie input{width:100%;border:1px solid var(--gris-med);border-radius:8px;padding:6px 8px;font:inherit;font-size:.82rem;margin-top:4px}

.ficha{margin-top:26px;display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:10px;max-width:560px}
.ficha div{background:rgba(255,255,255,.12);border-radius:12px;padding:10px 14px;font-size:.9rem}
.ficha small{display:block;opacity:.75;font-size:.72rem;text-transform:uppercase;letter-spacing:.06em}

/* Secciones */
section.sec{padding:54px 0 10px;scroll-margin-top:50px}
.num{display:inline-block;background:var(--granate);color:#fff;font-weight:700;width:34px;height:34px;line-height:34px;text-align:center;border-radius:50%;font-size:.95rem;margin-right:10px;vertical-align:middle}
.lead{color:var(--gris);max-width:70ch;font-size:1.05rem}
.card{background:var(--blanco);border-radius:var(--radio);box-shadow:var(--sombra);padding:22px;border:1px solid #ececef}
.cols{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
.etq{display:inline-block;font-size:.7rem;font-weight:700;letter-spacing:.05em;text-transform:uppercase;padding:3px 10px;border-radius:99px;margin-bottom:8px}
.etq.ej{background:#fdf3e1;color:#8a5a10}
.etq.vis{background:#e3f0f3;color:#1d5360}
.etq.ver{background:#e5f3e8;color:#23602f}
.etq.pen{background:var(--gris-cl);color:var(--gris)}
.nota{font-size:.85rem;color:var(--gris);background:#fff;border-left:4px solid var(--ocre);padding:10px 14px;border-radius:8px;margin:14px 0}

/* Línea de tiempo */
.tl-botones{display:flex;gap:8px;overflow-x:auto;padding:4px 2px 12px}
.tl-botones button{flex:0 0 auto;cursor:pointer;border:1px solid var(--gris-med);background:#fff;border-radius:14px;padding:8px 14px;font:inherit;font-size:.88rem;color:var(--gris);text-align:left}
.tl-botones button small{display:block;font-size:.72rem;opacity:.75}
.tl-botones button.on{background:var(--granate);color:#fff;border-color:var(--granate)}
.tl-barra{height:6px;background:var(--gris-med);border-radius:9px;margin:2px 0 16px;overflow:hidden}
.tl-barra i{display:block;height:100%;background:linear-gradient(90deg,var(--ocre),var(--granate));width:0;transition:width .3s}
.tl-cuerpo{display:grid;grid-template-columns:90px 1fr;gap:18px;align-items:start}
.tl-icono{font-size:2.6rem;background:var(--granate-cl);border-radius:20px;text-align:center;padding:14px 0}
.tl-nav{display:flex;gap:8px;margin-top:10px}

/* Pestañas aulas */
.tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:14px}
.tabs button{cursor:pointer;border:1px solid var(--gris-med);background:#fff;border-radius:99px;padding:8px 16px;font:inherit;font-size:.9rem;font-weight:600;color:var(--gris)}
.tabs button.on{background:var(--granate);color:#fff;border-color:var(--granate)}
.panel{display:none}.panel.on{display:block}
ul.check{padding-left:0;list-style:none;margin:0}
ul.check li{padding:6px 0 6px 28px;position:relative}
ul.check li::before{content:"▸";position:absolute;left:6px;color:var(--granate);font-weight:700}

/* Simulador */
.sim{display:grid;grid-template-columns:1.2fr .8fr;gap:20px}
.fila{display:grid;grid-template-columns:1.2fr 1fr 1fr;gap:10px;align-items:end;padding:12px 0;border-bottom:1px solid var(--gris-cl)}
.fila:last-of-type{border-bottom:0}
.fila label{font-size:.8rem;color:var(--gris);display:block;margin-bottom:3px}
.fila .nombre{font-weight:700;align-self:center}
.fila .nombre small{display:block;font-weight:400;color:var(--gris);font-size:.75rem}
input[type=number],input[type=text],select,textarea{width:100%;border:1px solid var(--gris-med);border-radius:10px;padding:9px 11px;font:inherit;font-size:.95rem;background:#fff}
textarea{resize:vertical;min-height:70px}
.total{background:var(--granate);color:#fff;border-radius:var(--radio);padding:20px}
.total .monto{font-family:Georgia,serif;font-size:2.4rem;font-weight:700;line-height:1.1}
.total .row{display:flex;justify-content:space-between;gap:10px;padding:6px 0;border-bottom:1px solid rgba(255,255,255,.2);font-size:.92rem}
.total .row:last-child{border:0}
.barras{margin-top:16px}
.barra{margin:9px 0}
.barra .top{display:flex;justify-content:space-between;font-size:.85rem;margin-bottom:3px}
.barra .bg{background:var(--gris-cl);border-radius:99px;height:14px;overflow:hidden}
.barra .bg i{display:block;height:100%;background:linear-gradient(90deg,var(--ocre),var(--granate));border-radius:99px;transition:width .3s}
.interp{background:var(--granate-cl);border-radius:12px;padding:12px 14px;font-size:.92rem;margin-top:12px}
.sw{display:flex;align-items:center;gap:8px;font-size:.9rem;margin-top:6px}

/* Bienestar */
.bien{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px}
.bien details{background:#fff;border-radius:var(--radio);box-shadow:var(--sombra);border:1px solid #ececef;padding:16px 18px}
.bien summary{cursor:pointer;font-weight:700;color:var(--granate-osc);list-style:none;display:flex;justify-content:space-between;gap:8px}
.bien summary::after{content:"+";color:var(--granate);font-size:1.3rem;line-height:1}
.bien details[open] summary::after{content:"–"}
.bien details p{margin:10px 0 0;font-size:.95rem}
.planif{margin-top:20px}
.planif .item{display:flex;gap:10px;align-items:center;padding:6px 0}
.planif input[type=checkbox]{width:20px;height:20px;accent-color:var(--granate)}

/* Voces */
.voz textarea{margin-top:6px}
.voz .preg{font-size:.9rem;color:var(--gris);padding-left:18px;margin:8px 0}
.voz .preg li{margin:4px 0}
.voz label{font-size:.8rem;color:var(--gris);display:block;margin-top:10px}
.estado{font-size:.78rem;margin-top:8px}

/* Más allá */
.mas{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:16px}
.mas .card{border-top:5px solid var(--granate)}
.mas .card:nth-child(2){border-top-color:var(--lago)}
.mas .card:nth-child(3){border-top-color:var(--ocre)}
.mas .card:nth-child(4){border-top-color:var(--gris)}
.mas .ico{font-size:1.8rem}

/* Galería */
.galeria{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:16px}
.galeria .card{padding:12px}
.galeria .foto{min-height:190px}
.galeria label{font-size:.78rem;color:var(--gris);display:block;margin-top:6px}

/* Reflexión */
.reflex{background:#fff;border-radius:var(--radio);box-shadow:var(--sombra);padding:34px clamp(20px,5vw,50px);border-left:8px solid var(--granate)}
.reflex p{font-family:Georgia,serif;font-size:1.12rem}
.reflex p:first-of-type::first-letter{font-size:3.2rem;float:left;line-height:.85;padding:6px 8px 0 0;color:var(--granate);font-weight:700}
.firma{font-family:Georgia,serif;font-style:italic;color:var(--gris);text-align:right}

/* Fuentes */
table{width:100%;border-collapse:collapse;font-size:.92rem}
th,td{text-align:left;padding:10px 12px;border-bottom:1px solid var(--gris-cl);vertical-align:top}
th{background:var(--granate-cl);color:var(--granate-osc);font-size:.8rem;text-transform:uppercase;letter-spacing:.04em}
.tabla-scroll{overflow-x:auto}
footer{margin-top:60px;background:var(--granate-osc);color:#f0dfe2;padding:30px 0;font-size:.88rem}
footer b{color:#fff}

@media (max-width:820px){
  .portada .grid,.sim{grid-template-columns:1fr}
  .tl-cuerpo{grid-template-columns:1fr}
  .tl-icono{width:80px}
  .fila{grid-template-columns:1fr 1fr}
  .fila .nombre{grid-column:1/-1}
  body{font-size:16px}
}
@media print{nav,.btn,.carga,.tl-botones{display:none}}
@media (prefers-reduced-motion:reduce){*{transition:none!important}html{scroll-behavior:auto}}
</style>
</head>
<body>

<div class="aviso">Trabajo académico estudiantil · No es una página oficial de la Universidad Nacional del Altiplano de Puno</div>

<nav aria-label="Secciones del reportaje">
  <div class="wrap">
    <a href="#portada">Portada</a>
    <a href="#dia">Un día</a>
    <a href="#aulas">Aulas</a>
    <a href="#costo">Costo de estudiar</a>
    <a href="#bienestar">Bienestar</a>
    <a href="#voces">Voces</a>
    <a href="#mas">Más allá</a>
    <a href="#galeria">Galería</a>
    <a href="#reflexion">Reflexión</a>
    <a href="#fuentes">Fuentes</a>
  </div>
</nav>

<!-- 1. PORTADA -->
<header class="portada" id="portada">
  <div class="wrap grid">
    <div>
      <span class="etiqueta">Reportaje digital · Ciencias de la Comunicación Social</span>
      <h1>Entre aulas y sueños: la vida universitaria en la UNA Puno</h1>
      <p class="sub">Una mirada a las experiencias y desafíos de quienes construyen su futuro en el altiplano</p>
      <p class="intro">Madrugadas frías, trayectos en transporte, exposiciones que ponen nerviosos y amistades que se arman entre clase y clase. Este reportaje explora cómo se vive la universidad en Puno: la rutina, los gastos, los retos y las aspiraciones. Recorre las secciones, juega con el simulador de gastos y descubre las voces que faltan por sumarse.</p>
      <p><a class="btn btn-claro" href="#dia">Comenzar el recorrido ↓</a></p>
      <div class="ficha" aria-label="Datos de la autora">
        <div><small>Autora</small> </div>
        <div><small>Carrera</small>Ciencias de la Comunicación Social</div>
        <div><small>Semestre</small>Segundo</div>
        <div><small>Universidad</small>Universidad Nacional del Altiplano, Puno</div>
      </div>
    </div>
    <div>
      <div class="foto" data-foto="portada">
        <img alt="" hidden>
        <div class="vacio"><b>Imagen principal</b>Sube una fotografía propia o con permiso de uso (por ejemplo, un paisaje de Puno o un espacio del campus).</div>
      </div>
      <label class="carga"><input type="file" accept="image/*" data-sube="portada"><span>Elegir imagen principal</span></label>
      <div class="pie"><span id="cred-portada">Pie de foto y crédito: pendiente de completar.</span></div>
    </div>
  </div>
</header>

<main class="wrap">

<!-- 2. UN DÍA -->
<section class="sec" id="dia">
  <h2><span class="num">1</span>Un día en la vida universitaria</h2>
  <p class="lead">Recorre una jornada posible, desde que suena la alarma hasta el descanso nocturno. Cada estudiante vive su día de forma distinta: depende de su horario, su vivienda, su economía y su carrera.</p>
  <div class="etq ej">Ejemplo ilustrativo</div>
  <div class="nota">Los horarios son referenciales y no representan a todos los estudiantes. Puedes editar el texto de cada momento para adaptarlo a una entrevista o experiencia real.</div>
  <div class="card">
    <div class="tl-botones" id="tlBotones" role="tablist" aria-label="Momentos del día"></div>
    <div class="tl-barra"><i id="tlProg"></i></div>
    <div class="tl-cuerpo">
      <div class="tl-icono" id="tlIco" aria-hidden="true">⏰</div>
      <div>
        <h3 id="tlTit"></h3>
        <p id="tlTxt" contenteditable="true" spellcheck="true"></p>
        <p class="pie">Consejo: haz clic en el texto para editarlo. Los cambios se guardan en este navegador.</p>
        <div class="tl-nav">
          <button class="btn btn-gris" id="tlAnt">← Anterior</button>
          <button class="btn btn-gr" id="tlSig">Siguiente →</button>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 3. AULAS -->
<section class="sec" id="aulas">
  <h2><span class="num">2</span>La experiencia dentro de las aulas</h2>
  <p class="lead">Estudiar en la universidad implica nuevas formas de aprender: más autonomía, más lecturas y más trabajo con otras personas.</p>
  <div class="card">
    <div class="tabs" role="tablist">
      <button class="on" data-panel="p1">Tareas y lecturas</button>
      <button data-panel="p2">Exposiciones</button>
      <button data-panel="p3">Trabajos grupales</button>
      <button data-panel="p4">Adaptación</button>
      <button data-panel="p5">Primeros semestres en Comunicación</button>
    </div>
    <div class="panel on" id="p1">
      <h3>Tareas y lecturas</h3>
      <p>En la universidad, gran parte del aprendizaje ocurre fuera del salón: lecturas, resúmenes, informes y búsquedas de información. Aprender a priorizar y a reconocer fuentes confiables es parte del proceso.</p>
    </div>
    <div class="panel" id="p2">
      <h3>Exposiciones</h3>
      <p>Hablar frente a la clase es un reto frecuente. Preparar un guion, practicar en voz alta y cuidar el material visual ayuda a ganar seguridad. Para quienes estudian comunicación, la exposición también es un ensayo de su futuro oficio.</p>
    </div>
    <div class="panel" id="p3">
      <h3>Trabajos grupales</h3>
      <p>Compartir tareas exige acuerdos, puntualidad y comunicación clara. Pueden surgir diferencias de horarios o de estilos de trabajo, pero también amistades y aprendizajes colectivos.</p>
    </div>
    <div class="panel" id="p4">
      <h3>Adaptación a la vida universitaria</h3>
      <p>Cambia el ritmo, el ambiente y el nivel de exigencia. Cada persona se adapta a su manera y en tiempos distintos; pedir orientación y conversar con compañeros de otros ciclos puede facilitar el camino.</p>
    </div>
    <div class="panel" id="p5">
      <h3>Primeros semestres en Ciencias de la Comunicación Social</h3>
      <p>Los primeros ciclos suelen acercar al estudiante a la lectura crítica, la redacción, la expresión oral y las nociones básicas de la comunicación. Estos aprendizajes sirven de base para el periodismo, la comunicación organizacional y los medios digitales.</p>
      <div class="etq pen">Por completar</div>
      <label for="planEst" style="font-size:.85rem;color:var(--gris)">Cursos del plan de estudios (tomar de la fuente oficial de la escuela profesional):</label>
      <textarea id="planEst" placeholder="Ej.: escribe aquí los cursos reales de primer y segundo semestre, con la fuente consultada."></textarea>
    </div>
  </div>
</section>

<!-- 4. COSTO -->
<section class="sec" id="costo">
  <h2><span class="num">3</span>El costo de estudiar</h2>
  <p class="lead">Estudiar también es administrar un presupuesto. Ingresa tus propios valores o los de la persona entrevistada y observa el total.</p>
  <div class="nota"><b>Unidades y período:</b> todos los montos están en <b>soles peruanos (S/)</b>. El simulador calcula un <b>total mensual</b> y una <b>proyección por semestre</b> (meses configurables). Los valores iniciales son <b>ejemplos ilustrativos editables</b>, no datos oficiales ni promedios reales.</div>
  <div class="sim">
    <div class="card">
      <span class="etq vis">Datos ingresados por el visitante</span>
      <div class="fila">
        <div class="nombre">🚌 Transporte<small>S/ por día × días de clase al mes</small></div>
        <div><label for="tr1">Gasto por día (S/)</label><input type="number" id="tr1" min="0" step="0.10" value="4"></div>
        <div><label for="tr2">Días al mes</label><input type="number" id="tr2" min="0" max="31" step="1" value="20"></div>
      </div>
      <div class="fila">
        <div class="nombre">🍽️ Alimentación<small>S/ por día × días al mes</small></div>
        <div><label for="al1">Gasto por día (S/)</label><input type="number" id="al1" min="0" step="0.10" value="12"></div>
        <div><label for="al2">Días al mes</label><input type="number" id="al2" min="0" max="31" step="1" value="26"></div>
      </div>
      <div class="fila">
        <div class="nombre">📚 Materiales<small>S/ por mes (copias, libros, útiles)</small></div>
        <div><label for="ma1">Gasto mensual (S/)</label><input type="number" id="ma1" min="0" step="1" value="40"></div><div></div>
      </div>
      <div class="fila">
        <div class="nombre">📶 Internet<small>S/ por mes (datos o plan)</small></div>
        <div><label for="in1">Gasto mensual (S/)</label><input type="number" id="in1" min="0" step="1" value="30"></div><div></div>
      </div>
      <div class="fila">
        <div class="nombre">🏠 Alojamiento (opcional)<small>S/ por mes, solo si aplica</small></div>
        <div><label for="ho1">Gasto mensual (S/)</label><input type="number" id="ho1" min="0" step="1" value="0"></div>
        <div><label for="ho2">¿Incluir?</label><select id="ho2"><option value="no">No</option><option value="si">Sí</option></select></div>
      </div>
      <div class="fila">
        <div class="nombre">🗓️ Meses por semestre<small>Para la proyección</small></div>
        <div><label for="mes">Meses</label><input type="number" id="mes" min="1" max="8" step="1" value="5"></div><div></div>
      </div>
      <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:12px">
        <button class="btn btn-gris" id="limpiar">Poner todo en 0</button>
        <button class="btn btn-gris" id="ejemplo">Restaurar ejemplo</button>
      </div>
    </div>
    <div>
      <div class="total" aria-live="polite">
        <div style="font-size:.85rem;opacity:.85">Total mensual estimado</div>
        <div class="monto" id="tMes">S/ 0.00</div>
        <div style="margin:10px 0 14px;font-size:.85rem;opacity:.85" id="tSem"></div>
        <div class="row"><span>Transporte</span><b id="rTr">S/ 0.00</b></div>
        <div class="row"><span>Alimentación</span><b id="rAl">S/ 0.00</b></div>
        <div class="row"><span>Materiales</span><b id="rMa">S/ 0.00</b></div>
        <div class="row"><span>Internet</span><b id="rIn">S/ 0.00</b></div>
        <div class="row"><span>Alojamiento</span><b id="rHo">S/ 0.00</b></div>
      </div>
      <div class="card barras" style="margin-top:14px">
        <h3 style="font-size:1rem">Distribución de lo que ingresaste</h3>
        <div id="barras"></div>
        <div class="interp" id="interp"></div>
        <p class="pie">Gráfico construido solo con los valores que tú ingresaste; no representa estadísticas de la UNA Puno.</p>
      </div>
    </div>
  </div>
</section>

<!-- 5. BIENESTAR -->
<section class="sec" id="bienestar">
  <h2><span class="num">4</span>Desafíos y bienestar</h2>
  <p class="lead">Cuidarse también forma parte de estudiar. Estos son algunos desafíos que muchas personas mencionan en la vida universitaria; no todas los viven igual ni con la misma intensidad.</p>
  <div class="bien">
    <details open><summary>⏳ Organización del tiempo</summary><p>Combinar clases, tareas, traslados y descanso exige planificar. Dividir las tareas grandes en pasos pequeños y reservar horarios fijos de estudio puede ayudar.</p></details>
    <details><summary>📖 Carga académica</summary><p>Hay semanas con varias entregas a la vez. Revisar los sílabos al inicio y anotar fechas importantes permite anticiparse. Pedir orientación a docentes también es válido.</p></details>
    <details><summary>🏡 Distancia de la familia</summary><p>Quienes llegan desde otras provincias o comunidades pueden extrañar su hogar. Mantener el contacto y formar redes de apoyo con compañeros puede hacer el cambio más llevadero.</p></details>
    <details><summary>⚖️ Equilibrio estudio y vida personal</summary><p>Dormir lo suficiente, comer con horarios y tener momentos de ocio también mejora el rendimiento. Si el cansancio o la preocupación se vuelven constantes, conviene hablar con alguien de confianza o buscar orientación profesional.</p></details>
  </div>
  <div class="card planif">
    <span class="etq vis">Actividad interactiva</span>
    <h3>Mi lista de equilibrio semanal</h3>
    <p style="font-size:.92rem;color:var(--gris)">Marca lo que lograste esta semana. Se guarda solo en tu navegador.</p>
    <div id="checklist"></div>
    <div class="interp" id="chkRes"></div>
  </div>
</section>

<!-- 6. VOCES -->
<section class="sec" id="voces">
  <h2><span class="num">5</span>Voces universitarias</h2>
  <p class="lead">Un reportaje se construye con personas. Estas tarjetas están listas para registrar entrevistas reales, siempre con consentimiento.</p>
  <div class="nota"><b>Importante:</b> no hay testimonios en esta página porque aún no se han registrado entrevistas. No se inventaron citas ni se atribuyeron frases a personas reales. Completa solo con respuestas autorizadas por quien las da.</div>
  <div class="cols" id="vocesGrid"></div>
</section>

<!-- 7. MÁS ALLÁ -->
<section class="sec" id="mas">
  <h2><span class="num">6</span>Más allá de las clases</h2>
  <p class="lead">La vida universitaria también ocurre fuera del salón. Estos espacios están pendientes de completar con información verificada.</p>
  <div class="mas" id="masGrid"></div>
</section>

<!-- 8. GALERÍA -->
<section class="sec" id="galeria">
  <h2><span class="num">7</span>Galería y recorrido visual</h2>
  <p class="lead">Las fotografías cuentan lo que las palabras no alcanzan. Sube imágenes propias o con permiso de uso y completa el pie de foto y el crédito.</p>
  <div class="nota">Las imágenes se muestran solo en tu navegador y no se suben a ningún servidor. Marca como <b>referencial</b> toda imagen que no corresponda al hecho o lugar descrito. Si usas fotos de otras personas, pide autorización y cita al autor.</div>
  <div class="galeria" id="galGrid"></div>
</section>

<!-- 9. REFLEXIÓN -->
<section class="sec" id="reflexion">
  <h2><span class="num">8</span>Reflexión final</h2>
  <div class="reflex">
    <p>Llegar a la universidad es mucho más que ocupar un asiento en un aula. Es aprender a organizar el tiempo, a hablar frente a otros, a trabajar en equipo y a sostener una meta aun en los días de cansancio. En Puno, esa experiencia se vive entre el frío de la mañana, las distancias, los presupuestos ajustados y, también, el orgullo de las raíces y la diversidad cultural del altiplano.</p>
    <p>No existe una sola manera de ser estudiante. Cada historia tiene sus propios ritmos, sus apoyos y sus obstáculos. Por eso, contar la vida universitaria exige escuchar con respeto, preguntar con cuidado y evitar las generalizaciones.</p>
    <p>Quizá esa sea la mayor lección de estos primeros semestres: que los sueños se construyen paso a paso, con esfuerzo, con aprendizaje y con la compañía de quienes comparten el camino.</p>
    <div class="firma">— Ciencias de la Comunicación Social</div>
  </div>
</section>

<!-- 10. FUENTES -->
<section class="sec" id="fuentes">
  <h2><span class="num">9</span>Fuentes y metodología</h2>
  <p class="lead">Este proyecto distingue con claridad qué información está verificada, cuál ingresa el visitante y cuál es un ejemplo ilustrativo.</p>
  <div class="card">
    <div class="tabla-scroll">
    <table>
      <thead><tr><th>Tipo</th><th>Dónde aparece</th><th>Estado</th></tr></thead>
      <tbody>
        <tr><td><span class="etq ver">Verificada</span></td><td>Datos de la autora, carrera, semestre y universidad (proporcionados por la autora).</td><td>Confirmada por la autora</td></tr>
        <tr><td><span class="etq vis">Ingresada por el visitante</span></td><td>Simulador de gastos, lista de equilibrio, tarjetas de entrevistas, textos y fotos que se completen.</td><td>Depende de quien la ingresa; no es un dato estadístico</td></tr>
        <tr><td><span class="etq ej">Ilustrativa</span></td><td>Línea de tiempo del día, valores iniciales del simulador, textos descriptivos de las secciones.</td><td>Ejemplo general, no representa a todos los estudiantes</td></tr>
        <tr><td><span class="etq pen">Pendiente</span></td><td>Entrevistas, actividades culturales y deportivas, galería, plan de estudios.</td><td>Por completar con información real y fuente</td></tr>
      </tbody>
    </table>
    </div>
    <h3 style="margin-top:22px">Fuentes consultadas (completar)</h3>
    <p style="font-size:.92rem;color:var(--gris)">Anota aquí cada fuente real que uses (sitio oficial, documento, entrevista, fecha de consulta).</p>
    <textarea id="fuentesTxt" style="min-height:110px" placeholder="1. Nombre de la fuente – enlace o documento – fecha de consulta&#10;2. ..."></textarea>
    <h3 style="margin-top:20px">Créditos</h3>
    <ul class="check">
      <li>Autoría, redacción y diseño del reportaje: </li>
      <li>Fotografías: pendientes; cada una debe indicar autor y permiso de uso en la galería.</li>
      <li>Colores granate, blanco y gris con detalles inspirados en el altiplano; no corresponden a la identidad oficial de la universidad.</li>
    </ul>
    <p style="margin-top:14px"><b>Fecha de elaboración:</b> 18 de octubre de 2026.</p>
    <p class="pie">Proyecto académico estudiantil del segundo semestre de Ciencias de la Comunicación Social. No es una página oficial de la Universidad Nacional del Altiplano de Puno.</p>
  </div>
</section>

</main>

<footer>
  <div class="wrap">
    <b>Entre aulas y sueños</b> · Reportaje digital estudiantil · · Ciencias de la Comunicación Social · II semestre<br>
    Universidad Nacional del Altiplano, Puno · Trabajo académico, no oficial · 2026
  </div>
</footer>

<script>
(function(){
  /* almacenamiento seguro */
  var store={
    get:function(k){try{return localStorage.getItem(k)}catch(e){return null}},
    set:function(k,v){try{localStorage.setItem(k,v)}catch(e){}}
  };
  var $=function(s,c){return (c||document).querySelector(s)};
  var $$=function(s,c){return Array.prototype.slice.call((c||document).querySelectorAll(s))};

  /* ---------- Navegación activa ---------- */
  var links=$$('nav a');
  var secs=links.map(function(a){return $(a.getAttribute('href'))});
  function marcar(){
    var y=window.scrollY+120,idx=0;
    secs.forEach(function(s,i){if(s&&s.offsetTop<=y)idx=i});
    links.forEach(function(a,i){a.classList.toggle('activo',i===idx)});
  }
  window.addEventListener('scroll',marcar,{passive:true});marcar();

  /* ---------- Línea de tiempo ---------- */
  var momentos=[
    {h:'Mañana temprano',i:'⏰',t:'Preparativos',x:'Despertar, alistar cuadernos y materiales y abrigarse bien: en Puno las mañanas suelen ser frías. Muchos estudiantes aprovechan este momento para repasar apuntes o revisar el horario del día.'},
    {h:'Camino a la universidad',i:'🚌',t:'Transporte',x:'El traslado puede hacerse a pie, en transporte público u otros medios, según dónde viva cada estudiante. El tiempo y el costo del trayecto influyen en la organización del día.'},
    {h:'Horario de clases',i:'🏛️',t:'Clases',x:'Teoría, debates, exposiciones y trabajos en clase. Entre una sesión y otra hay pausas para conversar, avanzar tareas o ir a la biblioteca.'},
    {h:'Mediodía',i:'🍽️',t:'Alimentación',x:'Almorzar cerca de la universidad, llevar comida o volver a casa son algunas opciones. La alimentación influye en la energía para la tarde.'},
    {h:'Tarde',i:'📚',t:'Estudio y trabajos grupales',x:'Biblioteca, coordinación con compañeros, búsqueda de información y avance de informes. También hay quienes combinan estudios con otras responsabilidades.'},
    {h:'Regreso a casa',i:'🌇',t:'Retorno',x:'Regresar al hogar o al alojamiento al caer la tarde. Es un buen momento para desconectarse un poco.'},
    {h:'Noche',i:'🌙',t:'Actividades nocturnas y descanso',x:'Cenar, terminar tareas pendientes, conversar con la familia o amistades y preparar lo del día siguiente. Dormir lo suficiente es parte de rendir bien.'}
  ];
  var cur=0,bt=$('#tlBotones');
  momentos.forEach(function(m,i){
    var b=document.createElement('button');
    b.innerHTML=m.i+' '+m.t+'<small>'+m.h+'</small>';
    b.addEventListener('click',function(){ir(i)});
    bt.appendChild(b);
  });
  function ir(i){
    cur=Math.max(0,Math.min(momentos.length-1,i));
    var m=momentos[cur];
    $('#tlIco').textContent=m.i;
    $('#tlTit').textContent=m.t+' · '+m.h;
    var g=store.get('tl'+cur);
    $('#tlTxt').textContent=g||m.x;
    $('#tlProg').style.width=((cur+1)/momentos.length*100)+'%';
    $$('button',bt).forEach(function(b,k){b.classList.toggle('on',k===cur)});
    $('#tlAnt').disabled=cur===0;$('#tlSig').disabled=cur===momentos.length-1;
    $('#tlAnt').style.opacity=cur===0?.5:1;$('#tlSig').style.opacity=cur===momentos.length-1?.5:1;
  }
  $('#tlAnt').addEventListener('click',function(){ir(cur-1)});
  $('#tlSig').addEventListener('click',function(){ir(cur+1)});
  $('#tlTxt').addEventListener('input',function(){store.set('tl'+cur,this.textContent)});
  ir(0);

  /* ---------- Pestañas aulas ---------- */
  $$('.tabs button').forEach(function(b){
    b.addEventListener('click',function(){
      $$('.tabs button').forEach(function(x){x.classList.remove('on')});
      $$('.panel').forEach(function(x){x.classList.remove('on')});
      b.classList.add('on');$('#'+b.dataset.panel).classList.add('on');
    });
  });
  ['planEst','fuentesTxt'].forEach(function(id){
    var el=$('#'+id),v=store.get(id);if(v)el.value=v;
    el.addEventListener('input',function(){store.set(id,el.value)});
  });

  /* ---------- Simulador ---------- */
  var ids=['tr1','tr2','al1','al2','ma1','in1','ho1','ho2','mes'];
  var ejemplo={tr1:4,tr2:20,al1:12,al2:26,ma1:40,in1:30,ho1:0,ho2:'no',mes:5};
  var cero={tr1:0,tr2:0,al1:0,al2:0,ma1:0,in1:0,ho1:0,ho2:'no',mes:5};
  function num(id){var v=parseFloat($('#'+id).value);return isNaN(v)||v<0?0:v}
  function money(n){return 'S/ '+n.toFixed(2)}
  function calc(){
    var tr=num('tr1')*num('tr2'),al=num('al1')*num('al2'),ma=num('ma1'),inn=num('in1');
    var ho=$('#ho2').value==='si'?num('ho1'):0;
    var meses=Math.max(1,num('mes'));
    var tot=tr+al+ma+inn+ho;
    $('#rTr').textContent=money(tr);$('#rAl').textContent=money(al);
    $('#rMa').textContent=money(ma);$('#rIn').textContent=money(inn);$('#rHo').textContent=money(ho);
    $('#tMes').textContent=money(tot);
    $('#tSem').textContent='Proyección por semestre ('+meses+' meses): '+money(tot*meses);
    var data=[['Transporte',tr],['Alimentación',al],['Materiales',ma],['Internet',inn],['Alojamiento',ho]];
    var bx=$('#barras');bx.innerHTML='';
    if(tot<=0){
      bx.innerHTML='<p style="font-size:.9rem;color:var(--gris)">Ingresa valores mayores a 0 para ver la distribución.</p>';
      $('#interp').textContent='Aún no hay datos para interpretar.';
    }else{
      data.forEach(function(d){
        var p=d[1]/tot*100;
        var el=document.createElement('div');el.className='barra';
        el.innerHTML='<div class="top"><span>'+d[0]+'</span><span>'+money(d[1])+' ('+p.toFixed(1)+'%)</span></div><div class="bg"><i style="width:'+p+'%"></i></div>';
        bx.appendChild(el);
      });
      var mayor=data.slice().sort(function(a,b){return b[1]-a[1]})[0];
      $('#interp').textContent='Con los valores ingresados, el rubro que más pesa es «'+mayor[0].toLowerCase()+'» ('+(mayor[1]/tot*100).toFixed(1)+'% del total mensual). Los porcentajes se calculan solo a partir de tus datos y cambian si modificas los montos.';
    }
    var o={};ids.forEach(function(i){o[i]=$('#'+i).value});store.set('sim',JSON.stringify(o));
  }
  function poner(o){ids.forEach(function(i){$('#'+i).value=o[i]});calc()}
  var g=store.get('sim');
  if(g){try{var o=JSON.parse(g);ids.forEach(function(i){if(o[i]!==undefined)$('#'+i).value=o[i]})}catch(e){}}
  ids.forEach(function(i){$('#'+i).addEventListener('input',calc);$('#'+i).addEventListener('change',calc)});
  $('#limpiar').addEventListener('click',function(){poner(cero)});
  $('#ejemplo').addEventListener('click',function(){poner(ejemplo)});
  calc();

  /* ---------- Checklist ---------- */
  var items=['Dormí lo suficiente la mayoría de los días','Comí en horarios regulares','Avancé mis tareas sin dejar todo para último momento','Tuve un momento de descanso o ocio','Hablé con familia o amistades','Pedí ayuda o aclaré una duda cuando la necesité'];
  var chk=$('#checklist'),est={};
  try{est=JSON.parse(store.get('chk')||'{}')}catch(e){}
  items.forEach(function(t,i){
    var d=document.createElement('label');d.className='item';
    d.innerHTML='<input type="checkbox" '+(est[i]?'checked':'')+'><span>'+t+'</span>';
    d.querySelector('input').addEventListener('change',function(){est[i]=this.checked;store.set('chk',JSON.stringify(est));resumen()});
    chk.appendChild(d);
  });
  function resumen(){
    var n=items.filter(function(_,i){return est[i]}).length;
    $('#chkRes').textContent='Marcaste '+n+' de '+items.length+' hábitos. Es una guía personal, no un diagnóstico.';
  }
  resumen();

  /* ---------- Voces ---------- */
  var preguntas=['¿Qué te motivó a estudiar en la UNA Puno?','¿Cuál ha sido la mayor dificultad en tu vida universitaria?','¿Cómo organizas tu tiempo entre clases, tareas y descanso?','¿Qué es lo que más disfrutas de estudiar aquí?','¿Qué sueñas lograr al terminar tu carrera?'];
  var vg=$('#vocesGrid');
  for(var n=1;n<=3;n++)(function(n){
    var c=document.createElement('div');c.className='card voz';
    c.innerHTML='<span class="etq pen">Entrevista pendiente</span><h3>Voz universitaria '+n+'</h3>'+
      '<label for="vn'+n+'">Nombre o seudónimo (con autorización)</label><input type="text" id="vn'+n+'" placeholder="Por completar">'+
      '<label for="vc'+n+'">Carrera y semestre</label><input type="text" id="vc'+n+'" placeholder="Por completar">'+
      '<label>Preguntas sugeridas</label><ul class="preg">'+preguntas.map(function(p){return '<li>'+p+'</li>'}).join('')+'</ul>'+
      '<label for="vt'+n+'">Respuestas registradas</label><textarea id="vt'+n+'" placeholder="Espacio para completar con respuestas reales y autorizadas."></textarea>'+
      '<label><input type="checkbox" id="vk'+n+'"> Cuento con el consentimiento de la persona entrevistada</label>'+
      '<div class="estado" id="ve'+n+'"></div>';
    vg.appendChild(c);
    ['vn','vc','vt'].forEach(function(p){
      var el=$('#'+p+n),v=store.get(p+n);if(v)el.value=v;
      el.addEventListener('input',function(){store.set(p+n,el.value);est2()});
    });
    var k=$('#vk'+n);k.checked=store.get('vk'+n)==='1';
    k.addEventListener('change',function(){store.set('vk'+n,k.checked?'1':'0');est2()});
    function est2(){
      var t=$('#vt'+n).value.trim(),e=$('#ve'+n);
      if(!t){e.textContent='Estado: pendiente de entrevista.';e.style.color='#666'}
      else if(!k.checked){e.textContent='Falta confirmar el consentimiento antes de publicar.';e.style.color='#a1500b'}
      else{e.textContent='Listo para revisión final.';e.style.color='#23602f'}
    }
    est2();
  })(n);

  /* ---------- Más allá ---------- */
  var mas=[
    {i:'🎭',t:'Actividades culturales',d:'Danza, música, teatro, ferias y celebraciones de la región.'},
    {i:'⚽',t:'Deportes',d:'Torneos, entrenamientos y espacios deportivos.'},
    {i:'🤝',t:'Amistades y vida social',d:'Cómo se forman los grupos de amigos y redes de apoyo.'},
    {i:'🗣️',t:'Participación estudiantil',d:'Centros de estudiantes, talleres, voluntariados y colectivos.'}
  ];
  var mg=$('#masGrid');
  mas.forEach(function(m,i){
    var c=document.createElement('div');c.className='card';
    c.innerHTML='<div class="ico">'+m.i+'</div><h3>'+m.t+'</h3><p style="font-size:.92rem;color:var(--gris)">'+m.d+'</p>'+
      '<span class="etq pen">Por completar</span>'+
      '<textarea id="ms'+i+'" placeholder="Describe aquí una actividad real, con fecha, lugar y fuente."></textarea>';
    mg.appendChild(c);
    var el=$('#ms'+i),v=store.get('ms'+i);if(v)el.value=v;
    el.addEventListener('input',function(){store.set('ms'+i,el.value)});
  });

  /* ---------- Fotos ---------- */
  function cargarFoto(clave,archivo){
    var r=new FileReader();
    r.onload=function(e){
      var cont=$('[data-foto="'+clave+'"]'),img=$('img',cont);
      img.src=e.target.result;img.hidden=false;img.alt='Fotografía '+clave;
      cont.classList.add('tiene');
    };
    r.readAsDataURL(archivo);
  }
  $$('input[data-sube="portada"]').forEach(function(i){
    i.addEventListener('change',function(){if(i.files[0])cargarFoto('portada',i.files[0])});
  });
  var pc=$('#cred-portada'),pv=store.get('credPortada');
  pc.innerHTML='<input type="text" id="cp" placeholder="Pie de foto y crédito (ej.: Vista de Puno. Foto: autor/a. Referencial)" aria-label="Pie de foto de portada">';
  if(pv)$('#cp').value=pv;
  $('#cp').addEventListener('input',function(){store.set('credPortada',this.value)});

  var gg=$('#galGrid');
  var temas=['Paisaje de Puno','Campus o aulas','Estudiantes en actividad','Vida cotidiana','Cultura y tradiciones','Espacios de estudio'];
  temas.forEach(function(t,i){
    var c=document.createElement('div');c.className='card';
    c.innerHTML='<div class="foto" data-foto="g'+i+'"><img alt="" hidden><div class="vacio"><b>Foto '+(i+1)+': '+t+'</b>Pendiente de imagen con permiso de uso</div></div>'+
      '<label class="carga"><input type="file" accept="image/*" data-sube="g'+i+'"><span>Elegir imagen</span></label>'+
      '<label for="gp'+i+'">Pie de foto</label><input type="text" id="gp'+i+'" placeholder="Describe qué se ve">'+
      '<label for="gc'+i+'">Crédito (autor/a o fuente)</label><input type="text" id="gc'+i+'" placeholder="Nombre del autor o fuente">'+
      '<label for="gr'+i+'">Tipo de imagen</label><select id="gr'+i+'"><option>Por definir</option><option>Propia</option><option>Con permiso de uso</option><option>Referencial</option></select>';
    gg.appendChild(c);
    $('input[data-sube]',c).addEventListener('change',function(){if(this.files[0])cargarFoto('g'+i,this.files[0])});
    ['gp','gc','gr'].forEach(function(p){
      var el=$('#'+p+i),v=store.get(p+i);if(v)el.value=v;
      el.addEventListener('input',function(){store.set(p+i,el.value)});
      el.addEventListener('change',function(){store.set(p+i,el.value)});
    });
  });
})();
</script>
</body>
</html>
