import React, { useState } from 'react';
import './App.css';
import Header from './components/Header';
import ProductList from './components/ProductList';
import Cart from './components/Cart';

function App() {
  const [cartItems, setCartItems] = useState([]);

  const handleAddToCart = (product) => {
    setCartItems([...cartItems, product]);
  };

  return (
    <div className="App">
      <Header cartItemCount={cartItems.length} />
      <ProductList onAddToCart={handleAddToCart} />
      <Cart cartItems={cartItems} />
    </div>
  );
}

export default App;
