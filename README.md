<?php



$glosario = [
    ["Cableado de área de trabajo", "Cables desde dispositivos hasta roseta o punto de conexión", "Parte del cableado horizontal", "Depende de ubicación y categoría del cable"],
    ["Cableado horizontal", "Enlace entre área de trabajo y cuarto de telecomunicaciones", "ANSI/TIA-568", "90 m de cable + 10 m patch cord"],
    ["Cableado vertical (Backbone)", "Interconexión entre cuartos de telecomunicaciones y entrada del edificio", "ANSI/TIA-568", "UTP hasta 800 m (voz), STP hasta 700 m"],
    ["Cableado de campus", "Enlaces exteriores entre edificios", "ANSI/TIA-568, ISO/IEC 11801", "Fibra óptica multimodo o monomodo según distancia"],
    ["Cuarto de telecomunicaciones", "Espacio para centralizar cableado y equipos", "ANSI/TIA-569", "Debe incluir racks, patch panels y puesta a tierra"],
    ["Cuarto de entrada", "Punto de conexión con proveedores externos", "ANSI/TIA-569", "Incluye protección contra sobretensiones y sistemas de puesta a tierra"],
    ["Racks y gabinetes", "Estructuras para montar equipos y paneles", "ANSI/TIA-569", "Dimensiones estándar 19''"],
    ["Canalizaciones y ductos", "Vías para alojar cableado", "ANSI/TIA-569", "Respetar radio de curvatura y evitar sobrellenado"],
    ["Bandejas portacables", "Soporte horizontal para grandes cantidades de cables", "ANSI/TIA-569", "Capacidad definida por carga de cables"],
    ["Bandejas tipo escalera", "Estructuras metálicas para tramos largos", "ANSI/TIA-569", "Para backbone y zonas técnicas"],
    ["Cable UTP", "Par trenzado sin blindaje", "ANSI/TIA-568", "Cat5e, Cat6, Cat6A, hasta 100 m"],
    ["Cable FTP", "Par trenzado con lámina de blindaje", "ANSI/TIA-568", "Hasta 100 m"],
    ["Cable STP", "Par trenzado blindado individualmente", "ANSI/TIA-568", "Hasta 100 m"],
    ["Fibra óptica multimodo", "50/125 o 62.5/125 µm para distancias medias", "ISO/IEC 11801", "Hasta 550 m"],
    ["Fibra óptica monomodo", "9/125 µm para distancias largas", "ISO/IEC 11801", "Hasta decenas de km"],
    ["Cables de acometida", "Desde proveedor a entrada del edificio", "Normas locales", "Depende de proveedor y tipo de servicio"],
    ["Patch cords", "Latiguillos flexibles para conexión temporal", "ANSI/TIA-568", "Hasta 10 m en conjunto con canal"],
    ["Patch panel", "Panel modular para terminación de cables en rack", "ANSI/TIA-568", "1U o 2U típicos"],
    ["Jacks RJ-45", "Conector hembra modular para cables UTP/FTP/STP", "ANSI/TIA-568", "Compatible con T568A o T568B"],
    ["Conector RJ-45 (8P8C)", "Conector macho modular", "ANSI/TIA-568", "Para terminación de patch cords"],
    ["Adaptadores de fibra", "Conectores SC, LC, ST, MTRJ, etc.", "TIA-604 (FOCIS)", "Depende de tipo de fibra"],
    ["Pigtails de fibra", "Cables cortos con conector de fibra en un extremo", "TIA-604", "Usados para fusión en paneles"],
    ["Cables preconectorizados", "Cables de fibra o cobre con conectores instalados de fábrica", "ISO/IEC 11801", "Listos para instalación rápida"],
    ["Norma ANSI/TIA-568", "Estandariza cableado estructurado", "ANSI/TIA", "Define distancias, categorías y rendimiento"],
    ["Norma ANSI/TIA-606", "Administración y etiquetado", "ANSI/TIA", "Identificación de cables y puertos"],
    ["Norma ANSI/TIA-569", "Diseño de rutas y espacios", "ANSI/TIA", "Dimensiones y distribución de cuartos"],
    ["Norma ANSI/TIA-607", "Puesta a tierra y enlace equipotencial", "ANSI/TIA", "Obligatoria en sistemas de telecomunicaciones"],
    ["ISO/IEC 11801", "Cableado genérico para instalaciones", "ISO/IEC", "Clasifica Clases A-Fa"],
    ["ANSI/TIA-942", "Diseño de cableado para data centers", "ANSI/TIA", "Incluye redundancia y alta disponibilidad"],
    ["Pinout T568A", "Asignación de pines RJ-45 (esquema A)", "ANSI/TIA-568", "Ver colores estándar"],
    ["Pinout T568B", "Asignación de pines RJ-45 (esquema B)", "ANSI/TIA-568", "Ver colores estándar"],
    ["Código de colores 25 pares", "Identificación de pares en cables multipar", "ANSI/TIA", "5 grupos de 5 pares"],
    ["Radio de curvatura", "Curvatura mínima permitida", "ANSI/TIA-568", "4 veces el diámetro del cable"],
    ["Separación de energía y datos", "Distancia mínima entre cables eléctricos y de datos", "ANSI/TIA-569", "≥ 50 mm sin barrera física"],
    ["Atenuación", "Pérdida de señal en un medio", "ANSI/TIA-568", "Debe estar dentro de límites por categoría"],
    ["NEXT (Near-End Crosstalk)", "Diafonía en el extremo cercano", "ANSI/TIA-568", "Dentro de límites según categoría"],
    ["ELFEXT", "Diafonía a frecuencia elevada", "ANSI/TIA-568", "Parámetro de pruebas"],
    ["Organizadores de cable", "Guías y peines para mantener cables ordenados", "Buenas prácticas", "Facilita mantenimiento"],
    ["Etiquetas y marcadores", "Identificación de cables y puertos", "ANSI/TIA-606", "Evita confusiones"],
    ["Protectores contra sobretensión", "Protección de líneas de datos y voz", "Normas UL/IEC", "Instalados en entrada de edificio"],
    ["Tapones antipolvo", "Protección física de conectores libres", "Buenas prácticas", "Evita suciedad y daño"]
];

?>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Glosario de Cableado Estructurado</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        table { border-collapse: collapse; width: 100%; }
        th, td { border: 1px solid #999; padding: 8px; text-align: left; }
        th { background-color: #f2f2f2; }
        tr:nth-child(even) { background-color: #f9f9f9; }
    </style>
</head>
<body>
    <h1>Glosario de Cableado Estructurado</h1>
    <table>
        <thead>
            <tr>
                <th>Elemento / Término</th>
                <th>Descripción</th>
                <th>Norma / Estándar</th>
                <th>Distancia / Parámetros</th>
            </tr>
        </thead>
        <tbody>
            <?php foreach ($glosario as $fila): ?>
                <tr>
                    <td><?= htmlspecialchars($fila[0]) ?></td>
                    <td><?= htmlspecialchars($fila[1]) ?></td>
                    <td><?= htmlspecialchars($fila[2]) ?></td>
                    <td><?= htmlspecialchars($fila[3]) ?></td>
                </tr>
            <?php endforeach; ?>
        </tbody>
    </table>
</body>
</html>

