Projeto: Leitura de ambiente para o bem-estar no trabalho

Feito por: Enzo Barbeli — RM 554272 e Felipe Santana RM554259


Problema Motivador

Com o crescimento do trabalho híbrido e remoto, profissionais passam longos períodos em ambientes que nem sempre são monitorados ou adequados.
Problemas como:
Fadiga mental e física
Temperaturas inadequadas
Baixa qualidade do ar
Falta de pausas regulares
Podem impactar diretamente o bem-estar e a performance dos trabalhadores.

Solução Proposta 

Desenvolvemos uma estação inteligente de bem-estar para o trabalho capaz de:
Monitorar temperatura e umidade do ambiente
Emitir alertas (via buzzer) quando o ambiente está inadequado
Reforçar pausas recomendadas através de timer automático
Enviar dados para um servidor HTTP (via webhook/site)

Componentes Utilizados (Wokwi)

ESP32 DevKit V1
Sensor DHT22 (Temperatura e Umidade)
Buzzer ativo 5V
Jumpers
Conexão Wi-Fi Wokwi (Wokwi-GUEST)
<img width="1610" height="688" alt="image" src="https://github.com/user-attachments/assets/1d5457e3-e590-4beb-9525-25b36e99372b" />

Funcionalidades Implementadas:

Monitoramento ambiental,
Leitura contínua de temperatura e umidade,
Alerta pelo buzzer caso valores fiquem acima do limite desejado,
Pausa recomendada,
Envio HTTP com dados sendo enviados automaticamente para o servidor a cada leitura


Link para o video: https://youtu.be/G7ijs0Qh_Dk
Link para o projeto: https://wokwi.com/projects/448262765717020673
