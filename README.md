# D3-cloud simplified

Simpler version of D3-cloud

## Usage

Include D3 library, D3-cloud plugin and D3-cloud-simplified
    
    <script src="d3.js"></script>
    <script src="d3.layout.cloud.js"></script>
    <script src="d3.cloud.simplified.js"></script>

Call cloud.make() passing options (width, height, font and words list)

    cloud.make({
      width: 1000,
      height: 800,
      font: "Helvetica",
      words: [{text: "This", size: 40}, {text: "is", size: 40}, {text: "an", size: 40}, {text: "Example", size: 40}]
    })