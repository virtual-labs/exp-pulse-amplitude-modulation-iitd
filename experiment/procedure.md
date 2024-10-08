    
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body>
    <div class="procedure">
        <h2>PAM (Pulse Amplitude Modulation)</h2>
        <ol>
            <li><strong>Generate Message Signal:</strong> Input the <code>message frequency</code> and <code>square carrier pulse frequency</code> into the provided fields. Click the <button>Generate Message</button> button to create the message signal.</li>
            <li><strong>Generate Carrier Signal:</strong> Click the <button>Generate Carrier</button> button to produce the square pulse carrier signal.</li>
            <li><strong>Generate Modulated Signal:</strong> Click the <button>Generate Modulated Signal</button> button to produce the PAM signal.</li>
            <li><strong>Perform Demodulation:</strong> Click the <button>Perform Demodulation</button> button to recover the original message signal from the modulated PAM signal.</li>
        </ol>
    </div>
    <div class="procedure">
        <h2>PWM (Pulse Width Modulation)</h2>
        <ol>
            <li><strong>Generate Message Signal:</strong> Input the <code>message frequency</code> and <code>square carrier pulse frequency</code> into the provided fields. Click the <button>Generate Message</button> button to create the message signal.</li>
            <li><strong>Generate Carrier Signal:</strong> Click the <button>Generate Carrier</button> button to produce the square pulse carrier signal.</li>
            <li><strong>Generate Modulated Signal:</strong> Click the <button>Generate Modulated Signal</button> button to produce the PWM signal.</li>
            <li><strong>Perform Demodulation:</strong> Click the <button>Perform Demodulation</button> button to recover the original message signal from the modulated PWM signal.</li>
        </ol>
    </div>
    <div class="procedure">
        <h2>PPM (Pulse Position Modulation)</h2>
        <ol>
            <li><strong>Generate Message Signal:</strong> Input the <code>message frequency</code>, <code>sampling frequency</code>, <code>samples per pulse</code>, and <code>pulse width fraction</code> into the provided fields. Click the <button>Generate Message</button> button to create the message signal.</li>
            <li><strong>Generate Modulated Signal:</strong> Click the <button>Generate Modulated Signal</button> button to produce the PPM signal.</li>
            <li><strong>Perform Demodulation:</strong> Click the <button>Perform Demodulation</button> button to recover the original message signal from the modulated PPM signal.</li>
        </ol>
    </div>
    <div class="procedure">
        <h2>PCM (Pulse Code Modulation)</h2>
        <ol>
            <li><strong>Generate Message Signal:</strong> Input the <code>message frequency</code> and <code>quantization levels</code> into the provided fields. Click the <button>Generate Message</button> button to create the message signal.</li>
            <li><strong>Plot Quantized Signal:</strong> Click the <button>Plot Quantized Signal</button> button to visualize the quantized version of the message signal.</li>
            <li><strong>Generate Modulated Signal:</strong> Click the <button>Generate Modulated Signal</button> button to produce the PCM signal.</li>
            <li><strong>Perform Demodulation:</strong> Click the <button>Perform Demodulation</button> button to recover the original message signal from the modulated PCM signal.</li>
        </ol>
    </div>
</body>
</html>
