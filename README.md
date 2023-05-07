<h1>Advertencia</h1>

<p>Es importante tener en cuenta que los asistentes virtuales son herramientas útiles y prácticas, pero también pueden ser objeto de mal uso. Algunas personas pueden usarlos para acosar, intimidar o engañar a otros, mientras que otras pueden depender demasiado de ellos y descuidar habilidades importantes, como la comunicación interpersonal. Es importante recordar que los asistentes virtuales no son seres humanos y tienen limitaciones en su capacidad para entender el contexto y las emociones humanas. Por lo tanto, es esencial utilizar los asistentes virtuales de manera responsable y ética, respetando los límites y la privacidad de los demás.</p>

<h1>Alice ASISTENTE VIRTUAL</h1>

<p>Alice es un asistente virtual que utiliza la API de Chat-GPT para ofrecer respuestas precisas y relevantes a las preguntas de los usuarios. Gracias a la potencia de la tecnología GPT, Alice puede analizar el contexto y el tono de la conversación para brindar una experiencia de usuario personalizada y satisfactoria. Ya sea que los usuarios necesiten ayuda con una tarea cotidiana, información sobre un tema específico o simplemente una conversación amigable, Alice está siempre lista para ayudar. Además, la API de Chat-GPT permite que Alice aprenda y se adapte continuamente a las necesidades y preferencias de los usuarios, brindando una experiencia de asistencia virtual cada vez más eficiente y efectiva.</p>

# Habla con Alice
La palabra de activación es **Alice** seguido de lo que quieres preguntar. Por ejemplo:
* **Alice** quién es el presidente de Mexico?
* Parece que va a llover, **Alice** cual es el pronóstico del clima en Mexico?
* **Salir** (Esta palabra cierra la ejecución del programa.)

# Instalación
Añade la api de  CHAT-GPT a Alice y pegala dentro del archivo **config.py**.
## Instalación Dependencias
### Clonar Repositorio
```markdown
git clone https://github.com/HAME-RU/Alice.git
cd Alice
```
### Instalar librerias Python
```markdown
pip install openai
pip install SpeechRecognition
pip install gtts
```
### Ejecución
```markdown
python3 chat_gpt.py 2>/dev/null
```
Al iniciar el programa se suele mostraer algo de ruido referente a la activación del micrófono. Para no ver estos errores, reedireccionamos todos los errores al **/dev/null**.
