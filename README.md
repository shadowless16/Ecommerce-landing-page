# Ecommerce-landing-page

.product-catalog {
    display: grid;
    gap: 20px;
    padding: 20px;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Ensures responsiveness */
}

.product-card {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 16px;
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

.product-card img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    object-fit: contain; /* Ensures image aspect ratio is maintained */
    width: 100%;
    height: 200px; /* Set uniform height for all images */
}

.product-card h2 {
    font-size: 1.2em;
    margin: 15px 0 10px;
    color: #333;
}

.product-card p {
    font-size: 1em;
    color: #ff6600; /* Jumia-like orange color for price */
    font-weight: bold;
}