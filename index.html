<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de planos inclinados</title>
 
    <link rel="stylesheet" href="estilos.css">
</head>
<body>


<nav>
    <a href="#">Calculadora</a>
    <a href="#">futuro proyecto 2</a>
    <a href="#">futuro proyecto 3</a>
</nav>

<section>
    <h1>Calculadora de planos inclinados</h1>
    
    <form method="post">
        <input type="number" name="num1" placeholder="Ingrese valor de la masa (kg)" required>
        <input type="number" name="num2" placeholder="Ingrese los grados de inclinación (°)" required>
        
        <select name="Material1" required>
            <option value="Hielo">Hielo</option>
            <option value="Vidrio">Vidrio</option>
            <option value="Madera">Madera</option>
            <option value="Acero">Acero</option>
            <option value="Cuero">Cuero</option>
        </select>
        
        <select name="Material2" required>
            <option value="Hielo">Hielo</option>
            <option value="Vidrio">Vidrio</option>
            <option value="Madera">Madera</option>
            <option value="Acero">Acero</option>
            <option value="Cuero">Cuero</option>
        </select>
        
        <button type="submit" name="calcular">Calcular</button>
    </form>

    <?php
    function calculeitorT800($num1, $num2, $Material1, $Material2){
        
        $coef_fraccion = [
            "Hielo_Hielo" => 0.03,    
            "Hielo_Vidrio" => 0.1,   
            "Hielo_Madera" => 0.2,   
            "Hielo_Acero" => 0.05,    
            "Hielo_Cuero" => 0.3,     
            "Vidrio_Hielo" => 0.1,   
            "Vidrio_Vidrio" => 0.4,  
            "Vidrio_Madera" => 0.3,   
            "Vidrio_Acero" => 0.5,
            "Vidrio_Cuero" => 0.4,   
            "Madera_Hielo" => 0.2,    
            "Madera_Vidrio" => 0.3,   
            "Madera_Madera" => 0.5,   
            "Madera_Acero" => 0.6,   
            "Madera_Cuero" => 0.5,    
            "Acero_Hielo" => 0.05,    
            "Acero_Vidrio" => 0.5,    
            "Acero_Madera" => 0.6,    
            "Acero_Acero" => 0.7,     
            "Acero_Cuero" => 0.6,     
            "Cuero_Hielo" => 0.3,     
            "Cuero_Vidrio" => 0.4,    
            "Cuero_Madera" => 0.5,    
            "Cuero_Acero" => 0.6,    
            "Cuero_Cuero" => 0.6,    
        ];

        if (isset($_POST['calcular'])) {
            $num1 = $_POST['num1']; 
            $num2 = $_POST['num2']; 
            $Material1 = $_POST['Material1']; 
            $Material2 = $_POST['Material2']; 

            
            $g = 9.81; 
            $masa = $num1;
            $angulo = deg2rad($num2); 

            $fuerza_gravedad = $masa * $g * sin($angulo); 
            $fuerza_normal = $masa * $g * cos($angulo);   

            $coef_fraccion_key = $Material1 . "_" . $Material2;
            $coef_fraccion_value = $coef_fraccion[$coef_fraccion_key];

            $fuerza_friccion = $coef_fraccion_value * $fuerza_normal;

            if ($fuerza_gravedad <= $fuerza_friccion) {
                $resultado = "Está en equilibrio.";
            } else {
                $resultado = "No está en equilibrio.";
            }

            echo "<h3>Resultado: $resultado</h3>";
        }
    }

    calculeitorT800($_POST['num1'], $_POST['num2'], $_POST['Material1'], $_POST['Material2']);
    ?>

</section>

</body>
</html>
