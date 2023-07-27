# chatGPT with Node4Max

An example using OpenAI's GPT API with NodeJS in MaxMSP

#### [More visuals and code!](http://gumroad.com/tmhglnd)

#### [Become a Patron!](https://www.patreon.com/bePatron?u=9649817)

# About

Provide a prompt as a string/symbol via the `[textedit]` object (or by creating your own messages) and wait for the response. You can adjust parameters such as the `temperature`, the `role` and the `max_tokens` for the generated output.

**You will need your own `API_KEY` from OpenAI to be able to work with the API.**

# Install 

Download zip

```
1. download zip
2. unzip
```

Git clone

```
1. $ cd ~/Documents/Max\ 8/Library
2. $ git clone https://github.com/tmhglnd/image-scraper-n4m.git
```

Go to the directory and run

```
$ npm install
```

Create a `.env` file and save your `API_KEY` as follows:

```
OPENAI_API_KEY=******************************************
```

Open `chatgpt-n4m.maxpat`, if the script hasn't started click `start`

# Dependencies

This project requires node packages:

- [openai](https://www.npmjs.com/package/openai)
- [dotenv](https://www.npmjs.com/package/dotenv)

# Licenses

The MIT License

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.