<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapa Mental: Historia Natural del Traumatismo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f9f9f9;
        }
        #jsmind {
            border: 1px solid #ccc;
            background-color: #fff;
            border-radius: 5px;
            padding: 10px;
            overflow: auto;
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jsmind/0.4.0/jsmind.js"></script>
</head>
<body>
    <h1>Mapa Mental: Historia Natural del Traumatismo</h1>
    <div id="jsmind" style="width: 800px; height: 600px;"></div>
    
    <script>
        var mind = {
            "meta": {
                "name": "jsMind",
                "version": "0.4.0"
            },
            "format": "node_tree",
            "data": {
                "id": "root",
                "topic": "Historia Natural del Traumatismo",
                "children": [
                    {
                        "id": "pre_injury",
                        "topic": "Fase Pre-injury",
                        "children": [
                            { "id": "factores_riesgo", "topic": "Factores de Riesgo", "children": [
                                { "id": "demograficos", "topic": "Demográficos" },
                                { "id": "cond_medicas", "topic": "Condiciones Médicas" },
                                { "id": "comportamientos_riesgo", "topic": "Comportamientos de Riesgo" }
                            ]},
                            { "id": "exposicion", "topic": "Exposición a Situaciones de Riesgo", "children": [
                                { "id": "ambientes", "topic": "Ambientes" },
                                { "id": "actividades_recreativas", "topic": "Actividades Recreativas" }
                            ]}
                        ]
                    },
                    {
                        "id": "fase_traumatismo",
                        "topic": "Fase del Traumatismo",
                        "children": [
                            { "id": "tipo_traumatismo", "topic": "Tipo de Traumatismo", "children": [
                                { "id": "cerrado", "topic": "Cerrado" },
                                { "id": "abierto", "topic": "Abierto" },
                                { "id": "penetrante", "topic": "Penetrante" }
                            ]},
                            { "id": "mecanismo_lesion", "topic": "Mecanismo de Lesión", "children": [
                                { "id": "fisico", "topic": "Físico" },
                                { "id": "termico", "topic": "Térmico" },
                                { "id": "quimico", "topic": "Químico" }
                            ]},
                            { "id": "gravedad_lesion", "topic": "Gravedad de la Lesión", "children": [
                                { "id": "leve", "topic": "Leve" },
                                { "id": "moderada", "topic": "Moderada" },
                                { "id": "grave", "topic": "Grave" }
                            ]}
                        ]
                    },
                    {
                        "id": "fase_aguda",
                        "topic": "Fase Aguda",
                        "children": [
                            { "id": "respuesta_fisiologica", "topic": "Respuesta Fisiológica", "children": [
                                { "id": "shock", "topic": "Shock hipovolémico" },
                                { "id": "inflamacion", "topic": "Inflamación" }
                            ]},
                            { "id": "atencion_prehospitalaria", "topic": "Atención Prehospitalaria", "children": [
                                { "id": "primeros_auxilios", "topic": "Primeros Auxilios" },
                                { "id": "transporte", "topic": "Transporte" }
                            ]},
                            { "id": "evaluacion_medica", "topic": "Evaluación Médica Inicial", "children": [
                                { "id": "diagnostico", "topic": "Diagnóstico" },
                                { "id": "imagenes", "topic": "Imágenes" }
                            ]}
                        ]
                    },
                    {
                        "id": "fase_tratamiento",
                        "topic": "Fase de Tratamiento",
                        "children": [
                            { "id": "manejo_quirurgico", "topic": "Manejo Quirúrgico", "children": [
                                { "id": "cirugia_emergencia", "topic": "Cirugía de emergencia" },
                                { "id": "intervenciones_electivas", "topic": "Intervenciones electivas" }
                            ]},
                            { "id": "tratamiento_conservador", "topic": "Tratamiento Conservador", "children": [
                                { "id": "inmovilizacion", "topic": "Inmovilización" },
                                { "id": "fisioterapia", "topic": "Fisioterapia" }
                            ]},
                            { "id": "monitoreo_complicaciones", "topic": "Monitoreo de Complicaciones", "children": [
                                { "id": "infecciones", "topic": "Infecciones" },
                                { "id": "hemorragias", "topic": "Hemorragias" }
                            ]}
                        ]
                    },
                    {
                        "id": "fase_recuperacion",
                        "topic": "Fase de Recuperación",
                        "children": [
                            { "id": "proceso_curacion", "topic": "Proceso de Curación", "children": [
                                { "id": "fase_inflamatoria", "topic": "Fase inflamatoria" },
                                { "id": "fase_proliferativa", "topic": "Fase proliferativa" },
                                { "id": "fase_remodelacion", "topic": "Fase de remodelación" }
                            ]},
                            { "id": "rehabilitacion_funcional", "topic": "Rehabilitación Funcional", "children": [
                                { "id": "terapia_ocupacional", "topic": "Terapia Ocupacional" },
                                { "id": "fisioterapia", "topic": "Fisioterapia" }
                            ]},
                            { "id": "adaptacion_cambios", "topic": "Adaptación a Cambios", "children": [
                                { "id": "discapacidad_temporal", "topic": "Discapacidad Temporal" },
                                { "id": "discapacidad_permanente", "topic": "Discapacidad Permanente" }
                            ]}
                        ]
                    },
                    {
                        "id": "fase_seguimiento",
                        "topic": "Fase de Seguimiento",
                        "children": [
                            { "id": "evaluacion_resultados", "topic": "Evaluación de Resultados a Largo Plazo", "children": [
                                { "id": "control_medico", "topic": "Control médico" },
                                { "id": "evaluacion_secuelas", "topic": "Evaluación de secuelas" }
                            ]},
                            { "id": "apoyo_psicologico", "topic": "Apoyo Psicológico", "children": [
                                { "id": "consejeria", "topic": "Consejería" },
                                { "id": "grupos_apoyo", "topic": "Grupos de apoyo" }
                            ]},
                            { "id": "prevencion_recaidas", "topic": "Prevención de Recaídas" }
                        ]
                    },
                    {
                        "id": "fase_prevencion",
                        "topic": "Fase de Prevención",
                        "children": [
                            { "id": "educacion_seguridad", "topic": "Educación sobre Seguridad", "children": [
                                { "id": "campanas_sensibilizacion", "topic": "Campañas de sensibilización" },
                                { "id": "entrenamientos", "topic": "Entrenamientos" }
                            ]},
                            { "id": "politicas_salud_publica", "topic": "Políticas de Salud Pública", "children": [
                                { "id": "mejora_infraestructura", "topic": "Mejora de Infraestructura" },
                                { "id": "regulacion", "topic": "Regulación" }
                            ]},
                            { "id": "monitoreo_factores_riesgo", "topic": "Monitoreo de Factores de Riesgo", "children": [
                                { "id": "estadisticas", "topic": "Estadísticas de traumatismos" },
                                { "id": "investigacion", "topic": "Investigación" }
                            ]}
                        ]
                    }
                ]
            }
        };

        var options = {
            container: 'jsmind',
            editable: false,
            theme: 'default'
        };

        var jm = new jsMind(options);
        jm.show(mind);
    </script>
</body>
</html>
