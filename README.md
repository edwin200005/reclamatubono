<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ejercicio de Seguridad</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen">
  <div class="bg-white rounded-2xl shadow-xl p-8 max-w-md text-center animate-fade-in">
    <h1 class="text-4xl font-bold text-red-600 mb-4">¡Caíste!</h1>
    <p class="text-gray-700 text-lg mb-4">
      Este fue un ejercicio de seguridad informática.  
      <br/> Aprende a identificar correos sospechosos para proteger tu información.
    </p>

    <div class="text-left text-sm text-gray-600 bg-red-50 border border-red-200 p-4 rounded-lg mb-6">
      <h2 class="font-semibold mb-2 text-red-800">¿Qué deberías haber notado?</h2>
      <ul class="list-disc list-inside space-y-1">
        <li>El remitente no era una cuenta oficial.</li>
        <li>El enlace parecía sospechoso.</li>
        <li>El mensaje tenía urgencia injustificada.</li>
        <li>No era una comunicación habitual de la empresa.</li>
      </ul>
    </div>

    <a href="https://tusitiointerno.com/capacitacion" class="inline-block bg-blue-600 text-white px-6 py-2 rounded-full hover:bg-blue-700 transition">
      Aprende a protegerte
    </a>
  </div>

  <style>
    @keyframes fade-in {
      0% { opacity: 0; transform: scale(0.9); }
      100% { opacity: 1; transform: scale(1); }
    }
    .animate-fade-in {
      animation: fade-in 0.5s ease-out;
    }
  </style>
</body>
</html>
