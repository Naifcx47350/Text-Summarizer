 <h1>Text Summarizer</h1>
    <p>
        This project is a text summarizer application that leverages the power of OpenAI's GPT-3.5-turbo model
        and PyPDF2 for extracting and summarizing text from various sources, including PDF files and plain text files.
    </p>

<h2>Features</h2>
    <ul>
        <li>Extract text from PDF files using <code>PyPDF2</code>.</li>
        <li>Load text from plain text files stored in the data directory.</li>
        <li>Generate concise and informative summaries of the extracted text using OpenAI's GPT-3.5-turbo model.</li>
    </ul>

 <h2>How It Works</h2>
    <p>
        The application first loads text from the data directory or extracts it from PDF files. It then sends this
        text to the OpenAI API with a prompt requesting a summary. The API responds with a well-structured summary
        highlighting the main points and key arguments of the provided text.
    </p>

   <h2>Installation</h2>
    <p>To set up this project, follow these steps:</p>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/yourusername/text-summarizer.git</code></pre>
        <li>Navigate to the project directory:</li>
        <pre><code>cd text-summarizer</code></pre>
        <li>Install the required dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Set up your OpenAI API key in a <code>.env</code> file:</li>
        <pre><code>OPEN_API_KEY=your_openai_api_key</code></pre>
    </ol>

<h2>Usage</h2>
    <p>
        To run the summarizer, use the following command:
    </p>
    <pre><code>python main.py</code></pre>
    <p>
        The program will load text from the data directory and generate a summary, which will be printed to the console.
    </p>

<h2>Contributing</h2>
    <p>
        Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or
        submit a pull request.
    </p>
</body>

</html>
