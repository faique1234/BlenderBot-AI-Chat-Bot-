<h1>BlenderBot Chatbot with Gradio Interface</h1>

<p>
A conversational AI chatbot built using the <b>Transformers</b> library and the 
<b>BlenderBot-400M-Distill</b> model. The project integrates a lightweight web-based 
graphical interface using <b>Gradio</b>, allowing users to interact with the chatbot 
through a browser in real time.
</p>

<h2>Features</h2>
<ul>
<li>Conversational AI powered by a pretrained BlenderBot model</li>
<li>Maintains conversation history for contextual responses</li>
<li>Interactive browser-based GUI using Gradio</li>
<li>Simple setup with minimal dependencies</li>
<li>Easily customizable for NLP experimentation</li>
</ul>

<h2>Technologies Used</h2>
<ul>
<li>Python</li>
<li>Hugging Face Transformers</li>
<li>BlenderBot-400M-Distill</li>
<li>Gradio</li>
</ul>

<h2>Installation</h2>

<p>Clone the repository:</p>

<pre>
git clone https://github.com/yourusername/blenderbot-gradio-chatbot.git
cd blenderbot-gradio-chatbot
</pre>

<p>Install required dependencies:</p>

<pre>
pip install transformers torch gradio
</pre>

<h2>Usage</h2>

<p>Run the chatbot application:</p>

<pre>
python chatbot.py
</pre>

<p>
After running the script, a local web interface will launch 
(usually at <b>http://127.0.0.1:7860</b>) where users can start chatting with the AI.
</p>

<h2>Project Structure</h2>

<pre>
chatbot.py   - Main chatbot script
README.md    - Project documentation
</pre>

<h2>Future Improvements</h2>
<ul>
<li>Add persistent chat history</li>
<li>Deploy the chatbot online</li>
<li>Integrate more advanced language models</li>
<li>Add streaming responses</li>
</ul>

<h2>License</h2>
<p>
This project is open-source and intended for educational and research purposes.
</p>
