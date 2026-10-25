
<!DOCTYPE html>
<html>
<head>
    <title>Product Listing</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body { font-family: Arial; text-align: center; }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .card {
            flex: 1 1 180px;
            max-width: 250px;
            padding: 15px;
            border: 1px solid gray;
            border-radius: 10px;
        }
        img { width: 100%; height: 130px; object-fit: cover; }
        button { background: blue; color: white; padding: 10px; border: 0; }
    </style>
</head>
<body>
    <h1>Product Listing</h1>
    <div class="products">
        <div class="card">
            <img src="images/laptop.jpg" alt="Laptop">
            <h3>Laptop</h3><p>₹45000</p><button>Buy</button>
        </div>
        <div class="card">
            <img src="images/phone.jpg" alt="Smartphone">
            <h3>Phone</h3><p>₹15000</p><button>Buy</button>
        </div>
        <div class="card">
            <img src="images/watch.jpg" alt="Watch">
            <h3>Watch</h3><p>₹2000</p><button>Buy</button>
        </div>
        <div class="card">
            <img src="images/bag.jpg" alt="Backpack">
            <h3>Bag</h3><p>₹1000</p><button>Buy</button>
        </div>
        <div class="card">
            <img src="images/shoes.jpg" alt="Shoes">
            <h3>Shoes</h3><p>₹2500</p><button>Buy</button>
        </div>
        <div class="card">
            <img src="images/headphones.jpg" alt="Headphones">
            <h3>Headphones</h3><p>₹3000</p><button>Buy</button>
        </div>
    </div>
</body>
</html>
