# Demo web application


Web application on git.zew.de 
<br> <small> https://git.zew.de/ub-public-finance/llm-text-classifier </small>
<br> <small> contains this presentation </small>


Web application be run on your notebooks

Written in `Python`

Extendable by researchers <br> and by student workers with IT affinity

<!--pagebreak-->

Web application connects to OpenAI <br>
 (online connection)

Requires an API key from OpenAI inc

OpenAI may charge you for heavy use

Any results are stored locally; <br> 
OpenAI is only asked _once_ per prompt

<!--pagebreak-->

Convenient uploading and arranging of data

* Texts to be mined
* Benchmark statements - belief statements 
* Pipelines of prompts

Some default data is provided

Expand according to your reserch


### Hallucinations not a problem

* Generative AI has some probabilistic element,  
  that can lead to erroneous results
    * Setting temperature to 0
    * Changing seed
    * => Replies show only tiny variation

Setting `temperature` to zero <br> 
=> hallucinations practically disappear

### Show

* [app](http://127.0.0.1:8000/)

*  sample_id: 83,    
*  benchmark_id: 2,


### Roadmap 1

* Crawlers
    * Find muni minutes, tagging, storing
* Import
    * Adapter for reading directories of PDF
    * Adapter for Excel data - column mapping
* Pipelines
    * Score-Functions
    * Branching

### Roadmap 2

* Results into Excel
    * Pipeline steps
    * Screenshots 
* Validation
    * Create datasets of results and known negatives
    * Visual datasets (screenshots from PDF, rendered results) 
    * Submit to `mechanical turk` 

### Roadmap 3

* Long unattended operation
* Easy review of failures
* Re-run failures and easy merge

### Roadmap 4

* Your input

