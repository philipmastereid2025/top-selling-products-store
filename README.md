const products = [
  {
    id: 1,
    name: "Wireless Earbuds (ANC)",
    category: "Electronics",
    price: 129,
    rating: 4.7,
    reviews: 25000,
    badge: "Hot",
    emoji: "🎧",
    description:
      "High-fidelity Bluetooth earbuds with active noise cancellation, long battery life, and fast pairing.",
    details: {
      color: "Midnight Blue",
      material: "ABS + TPU",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 2,
    name: "Smartwatch Series",
    category: "Wearables",
    price: 299,
    rating: 4.6,
    reviews: 40000,
    badge: "Best Seller",
    emoji: "⌚",
    description:
      "Fitness tracking, notifications, and health monitoring in a sleek, water-resistant smartwatch.",
    details: {
      color: "Graphite",
      material: "Aluminum case",
      shipping: "Free 3-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 3,
    name: "HEPA Air Purifier",
    category: "Home & Kitchen",
    price: 179,
    rating: 4.7,
    reviews: 15000,
    badge: "New",
    emoji: "🏠",
    description:
      "HEPA-14 filtration with carbon and UV-C to reduce allergens, smoke, and household odors.",
    details: {
      color: "White",
      material: "Steel + plastic",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 4,
    name: "Robot Vacuum Cleaner",
    category: "Smart Home",
    price: 349,
    rating: 4.5,
    reviews: 20000,
    badge: "Top Rated",
    emoji: "🧹",
    description:
      "Self-navigating vacuum with mapping, app control, and automatic docking for hands-free cleaning.",
    details: {
      color: "Slate",
      material: "Plastic + metal",
      shipping: "Free 3-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 5,
    name: "Premium Knife Set",
    category: "Kitchen",
    price: 89,
    rating: 4.6,
    reviews: 10000,
    badge: "Value",
    emoji: "🔪",
    description:
      "Full stainless-steel knife block with ergonomic handles and long-lasting sharpness.",
    details: {
      color: "Silver",
      material: "Stainless steel",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 6,
    name: "Non-Stick Bakeware Set",
    category: "Kitchen & Dining",
    price: 69,
    rating: 4.7,
    reviews: 30000,
    badge: "Popular",
    emoji: "🍳",
    description:
      "Multi-piece bakeware with reinforced non-stick coating for even baking and easy cleanup.",
    details: {
      color: "Charcoal",
      material: "Aluminum",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 7,
    name: "Wireless Security Camera Kit",
    category: "Security",
    price: 299,
    rating: 4.6,
    reviews: 12000,
    badge: "Popular",
    emoji: "📷",
    description:
      "2K HDR cameras with local storage, motion detection, and mobile alerts—no monthly fees.",
    details: {
      color: "Black",
      material: "Metal + plastic",
      shipping: "Free 3-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 8,
    name: "Insulated Tumbler",
    category: "Drinkware",
    price: 35,
    rating: 4.8,
    reviews: 50000,
    badge: "Trending",
    emoji: "🥤",
    description:
      "Double-wall stainless tumbler that keeps drinks cold or hot for hours, with spill-resistant lid.",
    details: {
      color: "Rose Gold",
      material: "Stainless steel",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 9,
    name: "K-Beauty Hydrating Serum",
    category: "Beauty",
    price: 28,
    rating: 4.7,
    reviews: 40000,
    badge: "Viral",
    emoji: "💧",
    description:
      "Lightweight, barrier-friendly serum for glowing, hydrated skin—viral favorite in skincare routines.",
    details: {
      color: "Clear",
      material: "Glass bottle",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 10,
    name: "Smart Bluetooth Tracker",
    category: "Accessories",
    price: 38,
    rating: 4.6,
    reviews: 18000,
    badge: "New",
    emoji: "🛰️",
    description:
      "Ultra-thin tracker that helps you locate keys, bags, and pets via phone app integration.",
    details: {
      color: "White",
      material: "ABS plastic",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 11,
    name: "Gaming Headset (Surround)",
    category: "Gaming",
    price: 99,
    rating: 4.5,
    reviews: 22000,
    badge: "Hot",
    emoji: "🎮",
    description:
      "Over-ear headset with surround sound, noise-canceling mic, and RGB accents for PC and console.",
    details: {
      color: "Black",
      material: "Memory foam",
      shipping: "Free 3-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 12,
    name: "MagSafe Phone Case",
    category: "Mobile",
    price: 29,
    rating: 4.6,
    reviews: 30000,
    badge: "Popular",
    emoji: "📱",
    description:
      "Shock-absorbing case with magnetic ring for wireless charging and accessory compatibility.",
    details: {
      color: "Blue",
      material: "Silicone",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 13,
    name: "Portable Power Bank",
    category: "Electronics",
    price: 59,
    rating: 4.7,
    reviews: 35000,
    badge: "Must Have",
    emoji: "🔋",
    description:
      "High-capacity USB-C power bank with fast charging for phones, tablets, and earbuds.",
    details: {
      color: "Black",
      material: "Aluminum shell",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 14,
    name: "Yoga Mat (Non-Slip)",
    category: "Fitness",
    price: 42,
    rating: 4.6,
    reviews: 18000,
    badge: "Top Rated",
    emoji: "🧘",
    description:
      "Cushioned, non-slip mat for yoga, pilates, and home workouts with easy-clean surface.",
    details: {
      color: "Forest Green",
      material: "PVC",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 15,
    name: "Resistance Band Set",
    category: "Fitness",
    price: 29,
    rating: 4.7,
    reviews: 12000,
    badge: "Hot",
    emoji: "🏋️",
    description:
      "Color-coded bands for strength training, stretching, and rehab exercises at home or on the go.",
    details: {
      color: "Multi",
      material: "Latex",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 16,
    name: "Pet Hair Remover Roller",
    category: "Pet Supplies",
    price: 22,
    rating: 4.6,
    reviews: 25000,
    badge: "Popular",
    emoji: "🐾",
    description:
      "Reusable roller that quickly lifts pet hair from furniture, carpets, and car seats.",
    details: {
      color: "White",
      material: "Plastic + rubber",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 17,
    name: "Stainless Water Bottle",
    category: "Outdoors",
    price: 29,
    rating: 4.8,
    reviews: 28000,
    badge: "Trending",
    emoji: "💧",
    description:
      "Durable, insulated bottle with leak-proof cap for daily hydration and outdoor adventures.",
    details: {
      color: "Matte Steel",
      material: "Stainless steel",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 18,
    name: "LED Strip Light Kit",
    category: "Lighting",
    price: 42,
    rating: 4.6,
    reviews: 22000,
    badge: "Popular",
    emoji: "💡",
    description:
      "Color-changing LED strips with remote or app control for rooms, desks, and TV backlighting.",
    details: {
      color: "RGB",
      material: "Flexible PCB",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 19,
    name: "Adjustable Laptop Stand",
    category: "Office",
    price: 49,
    rating: 4.7,
    reviews: 16000,
    badge: "Smart Pick",
    emoji: "💻",
    description:
      "Ergonomic stand that raises laptops to eye level, improving posture and airflow.",
    details: {
      color: "Black",
      material: "Aluminum + silicone",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  },
  {
    id: 20,
    name: "Hanging Closet Organizer",
    category: "Storage",
    price: 39,
    rating: 4.5,
    reviews: 9000,
    badge: "Value",
    emoji: "🧺",
    description:
      "Multi-shelf hanging organizer to maximize vertical closet space for clothes and accessories.",
    details: {
      color: "Gray",
      material: "Fabric + metal",
      shipping: "Free 2-day shipping",
      returnPolicy: "30-day return policy"
    }
  }
];

const categoryOrder = [
  "All",
  "Electronics",
  "Wearables",
  "Home & Kitchen",
  "Smart Home",
  "Kitchen",
  "Kitchen & Dining",
  "Security",
  "Drinkware",
  "Beauty",
  "Accessories",
  "Gaming",
  "Mobile",
  "Fitness",
  "Pet Supplies",
  "Outdoors",
  "Lighting",
  "Office",
  "Storage"
];

const state = {
  selectedCategory: "All",
  searchQuery: "",
  cart: JSON.parse(localStorage.getItem("novacart-cart") || "[]")
};

const cartCountEl = document.getElementById("cartCount");
const cartItemsEl = document.getElementById("cartItems");
const subtotalValueEl = document.getElementById("subtotalValue");
const shippingValueEl = document.getElementById("shippingValue");
const totalValueEl = document.getElementById("totalValue");
const cartPanel = document.getElementById("cartPanel");
const productGrid = document.getElementById("productGrid");
const categoryFilters = document.getElementById("categoryFilters");
const searchInput = document.getElementById("searchInput");
const overlay = document.getElementById("overlay");
const productModal = document.getElementById("productModal");
const checkoutModal = document.getElementById("checkoutModal");
const modalContent = document.getElementById("modalContent");

function formatPrice(value) {
  return new Intl.NumberFormat("en-US", {
    style: "currency",
    currency: "USD"
  }).format(value);
}

function saveCart() {
  localStorage.setItem("novacart-cart", JSON.stringify(state.cart));
}

function getFilteredProducts() {
  return products.filter((product) => {
    const matchesCategory =
      state.selectedCategory === "All" || product.category === state.selectedCategory;
    const query = state.searchQuery.trim().toLowerCase();
    const matchesSearch =
      !query ||
      product.name.toLowerCase().includes(query) ||
      product.category.toLowerCase().includes(query) ||
      product.description.toLowerCase().includes(query);

    return matchesCategory && matchesSearch;
  });
}

function renderFilters() {
  categoryFilters.innerHTML = categoryOrder
    .map(
      (category) => `
        <button
          class="filter-chip ${category === state.selectedCategory ? "active" : ""}"
          data-category="${category}"
          type="button"
        >
          ${category}
        </button>
      `
    )
    .join("");

  document.querySelectorAll(".filter-chip").forEach((button) => {
    button.addEventListener("click", () => {
      state.selectedCategory = button.dataset.category;
      renderFilters();
      renderProducts();
    });
  });
}

function renderProducts() {
  const filteredProducts = getFilteredProducts();

  if (!filteredProducts.length) {
    productGrid.innerHTML = `
      <div class="empty-state">
        <h3>No products match your search.</h3>
        <p>Try another keyword or switch categories.</p>
      </div>
    `;
    return;
  }

  productGrid.innerHTML = filteredProducts
    .map(
      (product) => `
        <article class="product-card">
          <div class="product-image" aria-label="${product.name}">${product.emoji}</div>
          <span class="product-badge">${product.badge}</span>

          <div class="product-header">
            <div>
              <div class="product-category">${product.category}</div>
              <h3 class="product-title">${product.name}</h3>
            </div>
          </div>

          <p class="product-description">${product.description}</p>

          <div class="product-meta">
            <span class="product-price">${formatPrice(product.price)}</span>
            <span class="product-rating">★ ${product.rating}</span>
          </div>

          <div class="product-actions">
            <button class="quick-view-btn" type="button" data-product-id="${product.id}">Quick view</button>
            <button type="button" data-product-id="${product.id}">Add to cart</button>
          </div>
        </article>
      `
    )
    .join("");

  productGrid.querySelectorAll("button[data-product-id]").forEach((button) => {
    const productId = Number(button.dataset.productId);
    const isQuickView = button.classList.contains("quick-view-btn");

    button.addEventListener("click", () => {
      if (isQuickView) {
        openProductModal(productId);
      } else {
        addToCart(productId);
      }
    });
  });
}

function addToCart(productId) {
  const product = products.find((item) => item.id === productId);
  if (!product) return;

  const existing = state.cart.find((item) => item.id === productId);

  if (existing) {
    existing.quantity += 1;
  } else {
    state.cart.push({ id: productId, quantity: 1 });
  }

  saveCart();
  updateCartUI();
}

function openCart() {
  cartPanel.classList.add("open");
  overlay.classList.remove("hidden");
}

function closeCart() {
  cartPanel.classList.remove("open");
  overlay.classList.add("hidden");
  if (!productModal.classList.contains("hidden")) {
    productModal.classList.add("hidden");
  }
  if (!checkoutModal.classList.contains("hidden")) {
    checkoutModal.classList.add("hidden");
  }
}

function updateCartUI() {
  const itemCount = state.cart.reduce((sum, item) => sum + item.quantity, 0);
  cartCountEl.textContent = itemCount;

  if (!state.cart.length) {
    cartItemsEl.innerHTML = `
      <div class="empty-cart">
        <p>Your cart is empty.</p>
      </div>
    `;
    subtotalValueEl.textContent = formatPrice(0);
    shippingValueEl.textContent = formatPrice(0);
    totalValueEl.textContent = formatPrice(0);
    return;
  }

  let subtotal = 0;
  cartItemsEl.innerHTML = state.cart
    .map((cartItem) => {
      const product = products.find((item) => item.id === cartItem.id);
      if (!product) return "";

      subtotal += product.price * cartItem.quantity;

      return `
        <div class="cart-item">
          <div class="cart-thumb" aria-hidden="true">${product.emoji}</div>
          <div>
            <h4>${product.name}</h4>
            <div class="cart-item-meta">
              <span>${formatPrice(product.price)}</span>
              <div class="qty-controls">
                <button type="button" data-action="decrease" data-product-id="${product.id}">−</button>
                <span>${cartItem.quantity}</span>
                <button type="button" data-action="increase" data-product-id="${product.id}">+</button>
              </div>
            </div>
            <button class="remove-item" type="button" data-action="remove" data-product-id="${product.id}">Remove</button>
          </div>
          <strong>${formatPrice(product.price * cartItem.quantity)}</strong>
        </div>
      `;
    })
    .join("");

  const shipping = subtotal > 75 ? 0 : 12;
  const total = subtotal + shipping;

  subtotalValueEl.textContent = formatPrice(subtotal);
  shippingValueEl.textContent = formatPrice(shipping);
  totalValueEl.textContent = formatPrice(total);

  cartItemsEl.querySelectorAll("[data-action]").forEach((button) => {
    const productId = Number(button.dataset.productId);
    const action = button.dataset.action;

    button.addEventListener("click", () => {
      const itemIndex = state.cart.findIndex((item) => item.id === productId);
      if (itemIndex === -1) return;

      if (action === "increase") {
        state.cart[itemIndex].quantity += 1;
      }

      if (action === "decrease") {
        state.cart[itemIndex].quantity -= 1;
        if (state.cart[itemIndex].quantity <= 0) {
          state.cart.splice(itemIndex, 1);
        }
      }

      if (action === "remove") {
        state.cart.splice(itemIndex, 1);
      }

      saveCart();
      updateCartUI();
    });
  });
}

function openProductModal(productId) {
  const product = products.find((item) => item.id === productId);
  if (!product) return;

  modalContent.innerHTML = `
    <div class="modal-content">
      <div class="modal-visual" aria-label="${product.name}">${product.emoji}</div>
      <div class="modal-copy">
        <p class="eyebrow">${product.category}</p>
        <h3>${product.name}</h3>
        <p>${product.description}</p>

        <div class="modal-meta">
          <span class="price">${formatPrice(product.price)}</span>
          <span class="rating">★ ${product.rating} (${product.reviews.toLocaleString()} reviews)</span>
        </div>

        <ul class="meta-list">
          <li><span>Color</span><strong>${product.details.color}</strong></li>
          <li><span>Material</span><strong>${product.details.material}</strong></li>
          <li><span>Shipping</span><strong>${product.details.shipping}</strong></li>
          <li><span>Returns</span><strong>${product.details.returnPolicy}</strong></li>
        </ul>

        <div class="modal-actions">
          <button class="primary-btn" type="button" data-product-id="${product.id}">Add to cart</button>
          <button class="secondary-btn" type="button" id="closeModalSecondary">Keep browsing</button>
        </div>
      </div>
    </div>
  `;

  productModal.classList.remove("hidden");
  overlay.classList.remove("hidden");

  document.querySelector("[data-product-id]").addEventListener("click", () => {
    addToCart(product.id);
    closeCart();
  });

  document.getElementById("closeModalSecondary").addEventListener("click", () => {
    productModal.classList.add("hidden");
    overlay.classList.add("hidden");
  });
}

function openCheckoutModal() {
  if (!state.cart.length) {
    alert("Your cart is empty. Add a product before checkout.");
    return;
  }

  checkoutModal.classList.remove("hidden");
  overlay.classList.remove("hidden");
}

function closeCheckoutModal() {
  checkoutModal.classList.add("hidden");
  overlay.classList.add("hidden");
}

searchInput.addEventListener("input", (event) => {
  state.searchQuery = event.target.value;
  renderProducts();
});

document.getElementById("cartToggle").addEventListener("click", () => {
  openCart();
});

document.getElementById("closeCart").addEventListener("click", closeCart);

document.getElementById("checkoutBtn").addEventListener("click", openCheckoutModal);

document.getElementById("closeModal").addEventListener("click", () => {
  productModal.classList.add("hidden");
  overlay.classList.add("hidden");
});

document.getElementById("closeCheckout").addEventListener("click", closeCheckoutModal);

document.getElementById("overlay").addEventListener("click", () => {
  closeCart();
  productModal.classList.add("hidden");
  checkoutModal.classList.add("hidden");
  overlay.classList.add("hidden");
});

document.getElementById("featuredProductBtn").addEventListener("click", () => {
  openProductModal(1);
});

document.querySelector("[data-product-id='1']").addEventListener("click", () => {
  addToCart(1);
});

document.getElementById("checkoutForm").addEventListener("submit", (event) => {
  event.preventDefault();

  const formData = new FormData(event.target);
  const name = formData.get("name");
  const email = formData.get("email");

  if (!name || !email) {
    alert("Please complete the form.");
    return;
  }

  state.cart = [];
  saveCart();
  updateCartUI();
  closeCheckoutModal();

  alert(`Thanks ${name}! Your order has been placed successfully.`);
  event.target.reset();
});

renderFilters();
renderProducts();
updateCartUI();

if (state.cart.length) {
  openCart();
}
