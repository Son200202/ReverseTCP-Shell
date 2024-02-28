# ReverseTCP-Shell

## Installation

First, clone this repository:

<!-- start:code block -->
### Clone this repository
<div>
  <textarea id="copyTextArea1" rows="4" cols="50">
git clone https://github.com/mfts/papermark.git
cd papermark
  </textarea>
  <button id="copyButton1">Copy</button>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/clipboard.js/2.0.8/clipboard.min.js"></script>
<script>
  var copyTextareaBtn = document.getElementById('copyButton1');
  var copyTextarea = document.getElementById('copyTextArea1');

  copyTextareaBtn.addEventListener('click', function(event) {
    copyTextarea.select();
    document.execCommand('copy');
  });
</script>


### Install dependencies
npm install

### Copy the example .env file
cp .env.example .env

### Initialize the database
npx prisma generate
npx prisma db push

### Run the app
npm run dev

### Open http://localhost:3000 in your browser
open http://localhost:3000
<!-- end:code block -->
