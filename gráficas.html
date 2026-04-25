<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Biomarcadores y Envejecimiento - Espectroscopía</title>
    <script src="https://cdn.plot.ly/plotly-2.24.1.min.js"></script>
    <style>
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            background-color: #121212; 
            color: #ffffff; 
            text-align: center; 
            padding: 20px; 
            margin: 0;
        }
        .container {
            width: 95%;
            max-width: 1400px;
            margin: 0 auto;
        }
        #chart { 
            width: 100%; 
            height: 700px; 
            background-color: #1e1e1e; 
            border-radius: 12px; 
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
            padding: 10px;
        }
        h1 { color: #ffca28; margin-bottom: 5px; }
        p { color: #aaaaaa; margin-bottom: 15px; font-size: 1.1em;}
        .instruction { color: #4dabf5; font-weight: bold; }
        .fundamento {
            background-color: #2a2a2a;
            border-left: 5px solid #2196f3;
            padding: 15px 20px;
            margin: 0 auto 25px auto;
            border-radius: 6px;
            font-size: 1.05em;
            text-align: left;
            color: #eeeeee;
            max-width: 1100px;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .fundamento strong { color: #ffffff; font-size: 1.15em;}
        #toggleBtn {
            background-color: #2196f3;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            transition: all 0.2s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }
        #toggleBtn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 10px rgba(0,0,0,0.4);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Análisis Óptico: Piel, Dientes y Bacterias</h1>
        <p>El gráfico muestra tanto la cuantificación de desgaste por la edad celular como los biomarcadores bacterianos dentales.</p>
        
        <div class="fundamento">
            <div>
                <strong>1. El Daño Celular (Envejecimiento):</strong><br>
                Observa la diferencia entre el "Caso: Piel Joven" (~18 a.u.) y "Piel Anciana" (~50 a.u.). Al envejecer celularmente, el daño molecular eleva la cantidad de fotones devueltos en la curva, incrementando el eje Y al triple de su altura basal.
            </div>
            <div>
                <strong>2. Infección Clínica (Biomarcadores):</strong><br>
                La luz roja arrojada por caries no viene del diente, sino de <b>Porfirinas</b>. Estos son desechos metabólicos bacterianos. Enciende las muestras de Sarro y Caries, y las flechas apuntarán exactamente dónde brillan frente a la infección activa.
            </div>
        </div>

        <div style="margin-bottom: 20px;">
            <p class="instruction">Marca/Desmarca los perfiles en el menú de la derecha para analizarlos uno por uno sin aglomerar el gráfico.</p>
            <button id="toggleBtn">Ocultar Punteros Bacterianos</button>
        </div>

        <div id="chart"></div>
    </div>

    <script>
        const conditions = [
            { name: 'Caso: Piel Joven (19 a)', exc: [350], excH: 18, em: [430], emH: 18, color: '#4CAF50', defaultShow: true }, 
            { name: 'Caso: Piel Anciana (81 a)', exc: [350, 380, 420], excH: 50, em: [430], emH: 50, color: '#F44336', defaultShow: true }, 
            { name: 'Diente Sano', exc: [337], excH: 10, em: [405, 435, 490, 525], emH: 6, color: '#8BC34A', defaultShow: false }, 
            { name: 'Caries (Nivel Pulpa)', exc: [337], excH: 10, em: [405, 435, 490, 530, 635], emH: 6, color: '#FF9800', defaultShow: false }, 
            { name: 'Caries (Nivel Dentina)', exc: [337], excH: 10, em: [405, 435, 490, 555], emH: 6, color: '#FFC107', defaultShow: false }, 
            { name: 'Sarro Supragingival', exc: [420], excH: 10, em: [495, 595, 635, 695], emH: 6, color: '#E91E63', defaultShow: false }, 
            { name: 'Sarro Subgingival (420 nm)', exc: [420], excH: 10, em: [495, 595, 650, 695], emH: 6, color: '#9C27B0', defaultShow: false }, 
            { name: 'Esmalte Sano y Cariado', exc: [405], excH: 10, em: [500], emH: 6, color: '#00BCD4', defaultShow: false }, 
            { name: 'Sarro Subgingival (635 nm)', exc: [635], excH: 10, em: [700, 783], emH: 6, color: '#3F51B5', defaultShow: false }, 
            { name: 'Dentina Cariada (655 nm)', exc: [655], excH: 10, em: [720, 810], emH: 6, color: '#03A9F4', defaultShow: false } 
        ];

        const myAnnotations = [
            { x: 410, y: 6, xref: 'x2', yref: 'y', text: 'Aminoácidos<br>(410nm)', showarrow: true, arrowhead: 2, arrowcolor: '#8BC34A', ax: -30, ay: -80, font: {color: '#8BC34A', size: 10} },
            { x: 590, y: 6, xref: 'x2', yref: 'y', text: 'Zn-Protoporfirina<br>(Bacterias 590nm)', showarrow: true, arrowhead: 2, arrowcolor: '#FFC107', ax: -30, ay: -50, font: {color: '#FFC107', size: 10} },
            { x: 625, y: 6, xref: 'x2', yref: 'y', text: 'Coproporfirina<br>(Caries 625nm)', showarrow: true, arrowhead: 2, arrowcolor: '#FF9800', ax: 0, ay: -80, font: {color: '#FF9800', size: 10} },
            { x: 635, y: 6, xref: 'x2', yref: 'y', text: 'Protoporfirina IX<br>(Infección Grave 635nm)', showarrow: true, arrowhead: 2, arrowcolor: '#F44336', ax: 50, ay: -110, font: {color: '#F44336', size: 10} }
        ];

        function gaussian(x, mean, dev) {
            return Math.exp(-0.5 * Math.pow((x - mean) / dev, 2));
        }

        let data = [];
        
        conditions.forEach((cond, index) => {
            let xVals = [];
            let yExc = [];
            let yEm = [];
            
            for (let x = 300; x <= 850; x++) {
                xVals.push(x);
                let tempExc = 0;
                cond.exc.forEach(peak => tempExc += cond.excH * gaussian(x, peak, 6));
                yExc.push(tempExc);
                
                let tempEm = 0;
                cond.em.forEach(peak => tempEm += cond.emH * gaussian(x, peak, 18));
                yEm.push(tempEm);
            }

            let isVisible = cond.defaultShow ? true : 'legendonly';

            data.push({
                x: xVals, y: yExc, xaxis: 'x', yaxis: 'y', mode: 'lines',
                name: cond.name, legendgroup: cond.name,
                line: { shape: 'spline', color: cond.color, width: 3 },
                fill: 'tozeroy', visible: isVisible, hovertemplate: '%{x} nm<extra></extra>'
            });

            data.push({
                x: xVals, y: yEm, xaxis: 'x2', yaxis: 'y', mode: 'lines',
                name: cond.name + ' (Emis)', legendgroup: cond.name, showlegend: false, 
                line: { shape: 'spline', color: cond.color, width: 3, dash: 'dot' }, 
                fill: 'tozeroy', visible: isVisible, hovertemplate: '%{x} nm<br><b>Fotones: %{y:.1f} a.u.</b><extra></extra>'
            });
        });

        data.push({
            x: [410, 590, 625, 635],
            y: [6, 6, 6, 6],
            xaxis: 'x2',
            yaxis: 'y',
            mode: 'markers',
            marker: { size: 10, color: ['#8BC34A', '#FFC107', '#FF9800', '#F44336'], line: {width: 2, color: '#ffffff'} },
            showlegend: false,
            hoverinfo: 'none'
        });

        const layout = {
            plot_bgcolor: '#1e1e1e',
            paper_bgcolor: '#1e1e1e',
            font: { color: '#ffffff' },
            grid: { rows: 1, columns: 2, pattern: 'independent' },
            xaxis: { title: 'ZONA DE EXCITACION (Entrada nm)', domain: [0, 0.46], gridcolor: '#333333', zerolinecolor: '#333333', tickfont: { size: 14 } },
            xaxis2: { title: 'ZONA DE EMISION (Fluorescencia nm)', domain: [0.54, 1], gridcolor: '#333333', zerolinecolor: '#333333', tickfont: { size: 14 } },
            yaxis: { title: 'Intensidad Reactiva (a.u.)', gridcolor: '#333333', zerolinecolor: '#333333', tickfont: { size: 14 }, showticklabels: true },
            margin: { l: 80, r: 250, t: 80, b: 60 },
            hovermode: 'x unified',
            annotations: myAnnotations,
            legend: { title: { text: 'Perfiles Biológicos' }, font: { size: 14 } }
        };

        Plotly.newPlot('chart', data, layout, {responsive: true});

        let annotationsVisible = true;
        const btn = document.getElementById('toggleBtn');
        btn.addEventListener('click', () => {
            annotationsVisible = !annotationsVisible;
            btn.innerText = annotationsVisible ? "Ocultar Punteros Bacterianos" : "Mostrar Punteros Bacterianos";
            btn.style.backgroundColor = annotationsVisible ? "#2196f3" : "#555555";
            
            Plotly.relayout('chart', { annotations: annotationsVisible ? myAnnotations : [] });
            Plotly.restyle('chart', { visible: annotationsVisible ? true : false }, [data.length - 1]);
        });
    </script>
</body>
</html>
