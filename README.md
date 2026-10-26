# online-shoping

const catalog = [
  {
    category: "Produce",
    color: "#f3eadf",
    items: [
      ["Apple", 1.25, "each", "🍎"], ["Banana", 0.35, "each", "🍌"], ["Orange", 0.9, "each", "🍊"],
      ["Mango", 2.5, "each", "🥭"], ["Grapes", 4.5, "1 lb bag", "🍇"], ["Pineapple", 3.5, "each", "🍍"],
      ["Watermelon", 6.5, "each", "🍉"], ["Strawberry", 4.5, "1 pint", "🍓"], ["Pomegranate", 2.5, "each", "🔴"],
      ["Kiwi", 0.9, "each", "🥝"], ["Guava", 1.5, "each", "🍐"], ["Papaya", 3.5, "each", "🥭"],
      ["Peach", 1.25, "each", "🍑"], ["Pear", 1.1, "each", "🍐"], ["Plum", 0.9, "each", "🟣"],
      ["Cherry", 5, "1 lb", "🍒"], ["Apricot", 1.2, "each", "🍑"], ["Lemon", 0.7, "each", "🍋"],
      ["Lime", 0.5, "each", "🍋"], ["Coconut", 3, "each", "🥥"], ["Blueberry", 4.5, "1 pint", "🫐"],
      ["Raspberry", 4.75, "6 oz", "🍓"], ["Blackberry", 4.5, "6 oz", "🫐"], ["Cantaloupe", 3.5, "each", "🍈"],
      ["Honeydew", 4, "each", "🍈"], ["Nectarine", 1.25, "each", "🍑"], ["Fig", 1.5, "each", "🟣"],
      ["Date", 5, "8 oz pack", "🌴"], ["Lychee", 6, "1 lb", "🍒"], ["Avocado", 1.75, "each", "🥑"],
      ["Potato", 1.5, "1 lb", "🥔"], ["Tomato", 3.5, "1 lb", "🍅"], ["Onion", 1.25, "1 lb", "🧅"],
      ["Carrot", 1.5, "1 lb bag", "🥕"], ["Cabbage", 2.5, "head", "🥬"], ["Spinach", 3, "bunch", "🥬"],
      ["Cucumber", 1, "each", "🥒"], ["Garlic", 0.75, "bulb", "🧄"], ["Ginger", 2.5, "1 lb", "🫚"],
      ["Broccoli", 2.5, "head", "🥦"], ["Cauliflower", 3, "head", "🥦"], ["Bell Pepper", 1.25, "each", "🫑"],
      ["Peas", 3, "1 lb", "🫛"], ["Eggplant", 2, "each", "🍆"], ["Radish", 2, "bunch", "🔴"],
      ["Lettuce", 2.5, "head", "🥬"], ["Beetroot", 2.5, "bunch", "🫜"], ["Pumpkin", 4, "each", "🎃"],
      ["Okra", 3, "1 lb", "🌿"], ["Zucchini", 1.5, "each", "🥒"], ["Kale", 3, "bunch", "🥬"],
      ["Celery", 2.5, "bunch", "🥬"], ["Asparagus", 4.5, "bunch", "🌿"], ["Corn", 0.9, "ear", "🌽"],
      ["Artichoke", 2, "each", "🌿"], ["Brussels Sprouts", 4, "1 lb", "🥬"], ["Turnip", 2, "bunch", "🫜"],
      ["Sweet Potato", 1.5, "1 lb", "🍠"], ["Parsnip", 2.5, "1 lb", "🥕"]
    ]
  },
  {
    category: "Grains",
    color: "#efe9d9",
    items: [
      ["Rice", 8, "5 lb bag", "🍚"], ["Wheat", 6, "5 lb bag", "🌾"], ["Oats", 4.5, "18 oz", "🥣"],
      ["Barley", 4, "1 lb", "🌾"], ["Corn", 3, "1 lb", "🌽"], ["Millet", 5, "1 lb", "🌾"],
      ["Quinoa", 7, "1 lb", "🌾"], ["Semolina", 4, "2 lb", "🌾"], ["Pasta", 3.25, "1 lb", "🍝"],
      ["Noodles", 3, "12 oz", "🍜"], ["Couscous", 4, "1 lb", "🍚"], ["Farro", 6, "1 lb", "🌾"],
      ["Sorghum", 5, "1 lb", "🌾"], ["Buckwheat", 5, "1 lb", "🌾"], ["Amaranth", 6, "1 lb", "🌾"],
      ["Teff", 7, "1 lb", "🌾"], ["Spelt", 6, "1 lb", "🌾"], ["Rye", 5, "1 lb", "🌾"],
      ["Triticale", 5, "1 lb", "🌾"], ["Bulgur", 4, "1 lb", "🌾"]
    ]
  },
  {
    category: "Grocery Items",
    color: "#f1eadc",
    items: [
      ["Atta (Wheat Flour)", 8, "5 lb bag", "🌾"], ["Dal (Lentils)", 5, "2 lb bag", "🫘"],
      ["Ghee (Clarified Butter)", 9, "14 oz jar", "🧈"], ["Chana (Chickpeas)", 4, "2 lb bag", "🫘"],
      ["Besan (Gram Flour)", 5, "2 lb bag", "🌾"], ["Dahi (Yogurt)", 4, "32 oz tub", "🥣"],
      ["Chawal (Rice)", 8, "5 lb bag", "🍚"], ["Sugar", 3, "4 lb bag", "🧂"],
      ["Salt", 1.5, "26 oz", "🧂"], ["Pepper", 3, "2 oz", "🌶️"],
      ["Baking Powder", 2.5, "8 oz", "🥄"], ["Baking Soda", 1.5, "16 oz", "🥄"],
      ["Yeast", 3, "3 sachets", "🍞"], ["Cooking Oil", 7, "32 oz", "🫒"],
      ["Vinegar", 3, "16 oz", "🍾"], ["Soy Sauce", 4, "15 oz", "🍶"],
      ["Mustard", 3, "12 oz", "🫙"], ["Ketchup", 3.5, "20 oz", "🍅"],
      ["Peanut Butter", 5, "16 oz", "🥜"], ["Jam", 4, "12 oz", "🫙"], ["Honey", 8, "12 oz", "🍯"]
    ]
  },
  {
    category: "Dairy & eggs",
    color: "#e8eee8",
    items: [
      ["Farm fresh eggs", 6, "free range · dozen", "🥚"], ["Creamy whole milk", 4.25, "local dairy · half gallon", "🥛"],
      ["Sharp cheddar", 5.5, "aged with care · 8 oz", "🧀"]
    ]
  },
  {
    category: "Bakery",
    color: "#eee5d8",
    items: [
      ["Country sourdough", 6.5, "baked this morning · loaf", "🍞"],
      ["Butter croissants", 7, "flaky & golden · 4 pack", "🥐"]
    ]
  }
];

const products = catalog.flatMap(({ category, color, items }) => items.map(([name, price, detail, emoji]) => ({
  id: `${category.toLowerCase().replace(/[^a-z0-9]+/g, "-")}-${name.toLowerCase().replace(/[^a-z0-9]+/g, "-")}`,
  name,
  detail,
  price,
  category,
  emoji,
  tag: category === "Produce" ? "FRESH PICK" : category.toUpperCase(),
  color
})));

const FREE_DELIVERY_AMOUNT = 50;
const cart = new Map();
const productGrid = document.querySelector("#product-grid");
const searchInput = document.querySelector("#search-input");
const resultsCount = document.querySelector("#results-count");
const emptyState = document.querySelector("#empty-state");
const cartDrawer = document.querySelector("#cart-drawer");
const cartBackdrop = document.querySelector("#cart-backdrop");
const cartItems = document.querySelector("#cart-items");
const cartCount = document.querySelector("#cart-count");
const cartEmpty = document.querySelector("#cart-empty");
const cartFooter = document.querySelector("#cart-footer");
const cartSubtotal = document.querySelector("#cart-subtotal");
const deliveryNote = document.querySelector("#delivery-note");
const toast = document.querySelector("#toast");
const checkoutBackdrop = document.querySelector("#checkout-backdrop");
const checkoutForm = document.querySelector("#checkout-form");
const paymentNote = document.querySelector("#payment-note");
const orderRequestMessage = document.querySelector("#order-request-message");
const sendOrderEmail = document.querySelector("#send-order-email");
let selectedCategory = "All";
let toastTimeout;

function formatPrice(price) {
  return new Intl.NumberFormat("en-US", { style: "currency", currency: "USD" }).format(price);
}

function getVisibleProducts() {
  const searchTerm = searchInput.value.trim().toLowerCase();
  return products.filter((product) => {
    const matchesCategory = selectedCategory === "All" || product.category === selectedCategory;
    const matchesSearch = `${product.name} ${product.detail} ${product.category}`.toLowerCase().includes(searchTerm);
    return matchesCategory && matchesSearch;
  });
}

function renderProducts() {
  const visibleProducts = getVisibleProducts();
  resultsCount.textContent = `${visibleProducts.length} ${visibleProducts.length === 1 ? "good thing" : "good things"}`;
  emptyState.hidden = visibleProducts.length > 0;
  productGrid.hidden = visibleProducts.length === 0;
  productGrid.innerHTML = visibleProducts.map((product) => `
    <article class="product-card">
      <div class="product-image" style="--product-bg: ${product.color}">
        <span class="product-tag">${product.tag}</span>
        <span class="product-emoji" role="img" aria-label="${product.name}">${product.emoji}</span>
        <button class="add-button" type="button" data-add="${product.id}" aria-label="Add ${product.name} to basket">+</button>
      </div>
      <div class="product-info">
        <div><h3>${product.name}</h3><p>${product.detail}</p></div>
        <span class="product-price">${formatPrice(product.price)}</span>
      </div>
    </article>
  `).join("");
}

function renderCart() {
  const itemCount = Array.from(cart.values()).reduce((total, quantity) => total + quantity, 0);
  const subtotal = products.reduce((total, product) => total + product.price * (cart.get(product.id) || 0), 0);
  cartCount.textContent = String(itemCount);
  cartCount.setAttribute("aria-label", `${itemCount} ${itemCount === 1 ? "item" : "items"} in basket`);
  cartEmpty.hidden = itemCount > 0;
  cartFooter.hidden = itemCount === 0;
  cartItems.innerHTML = products.filter((product) => cart.has(product.id)).map((product) => {
    const quantity = cart.get(product.id);
    return `
      <article class="cart-item">
        <div class="cart-item-art" style="--product-bg: ${product.color}" aria-hidden="true">${product.emoji}</div>
        <div>
          <h3>${product.name}</h3>
          <p>${formatPrice(product.price)} each</p>
          <div class="quantity-control" aria-label="Quantity for ${product.name}">
            <button type="button" data-quantity="${product.id}" data-change="-1" aria-label="Remove one ${product.name}">−</button>
            <span>${quantity}</span>
            <button type="button" data-quantity="${product.id}" data-change="1" aria-label="Add one ${product.name}">+</button>
          </div>
        </div>
        <strong class="cart-line-price">${formatPrice(product.price * quantity)}</strong>
      </article>
    `;
  }).join("");
  cartSubtotal.textContent = formatPrice(subtotal);

  if (subtotal >= FREE_DELIVERY_AMOUNT) {
    deliveryNote.textContent = "You've unlocked free local delivery. Thank you for shopping with our family!";
  } else {
    deliveryNote.textContent = `${formatPrice(FREE_DELIVERY_AMOUNT - subtotal)} away from free delivery on orders over ${formatPrice(FREE_DELIVERY_AMOUNT)}.`;
  }
}

function showToast(message) {
  window.clearTimeout(toastTimeout);
  toast.textContent = message;
  toast.classList.add("show");
  toastTimeout = window.setTimeout(() => toast.classList.remove("show"), 3200);
}

function openCart() {
  cartDrawer.classList.add("open");
  cartBackdrop.classList.add("open");
  cartDrawer.setAttribute("aria-hidden", "false");
  document.body.style.overflow = "hidden";
  document.querySelector("#close-cart").focus();
}

function closeCart() {
  cartDrawer.classList.remove("open");
  cartBackdrop.classList.remove("open");
  cartDrawer.setAttribute("aria-hidden", "true");
  document.body.style.overflow = "";
  document.querySelector("#open-cart").focus();
}

function openCheckout() {
  checkoutBackdrop.hidden = false;
  checkoutForm.querySelector('[name="customerName"]').focus();
  orderRequestMessage.hidden = true;
  sendOrderEmail.hidden = true;
  checkoutForm.querySelector('[type="submit"]').hidden = false;
}

function closeCheckout() {
  checkoutBackdrop.hidden = true;
  document.querySelector("#checkout-button").focus();
}

document.querySelector("#year").textContent = String(new Date().getFullYear());
renderProducts();
renderCart();

document.querySelector(".category-list").addEventListener("click", (event) => {
  const chip = event.target.closest("[data-category]");
  if (!chip) return;
  selectedCategory = chip.dataset.category;
  document.querySelectorAll(".category-chip").forEach((categoryChip) => {
    const isSelected = categoryChip === chip;
    categoryChip.classList.toggle("selected", isSelected);
    categoryChip.setAttribute("aria-pressed", String(isSelected));
  });
  renderProducts();
});

searchInput.addEventListener("input", renderProducts);

document.querySelector("#clear-filters").addEventListener("click", () => {
  selectedCategory = "All";
  searchInput.value = "";
  document.querySelectorAll(".category-chip").forEach((chip) => {
    const isSelected = chip.dataset.category === "All";
    chip.classList.toggle("selected", isSelected);
    chip.setAttribute("aria-pressed", String(isSelected));
  });
  renderProducts();
});

productGrid.addEventListener("click", (event) => {
  const button = event.target.closest("[data-add]");
  if (!button) return;
  const product = products.find((item) => item.id === button.dataset.add);
  if (!product) return;
  cart.set(product.id, (cart.get(product.id) || 0) + 1);
  renderCart();
  showToast(`${product.name} added to your basket.`);
});

cartItems.addEventListener("click", (event) => {
  const button = event.target.closest("[data-quantity]");
  if (!button) return;
  const productId = button.dataset.quantity;
  const newQuantity = (cart.get(productId) || 0) + Number(button.dataset.change);
  if (newQuantity <= 0) cart.delete(productId);
  else cart.set(productId, newQuantity);
  renderCart();
});

document.querySelector("#open-cart").addEventListener("click", openCart);
document.querySelector("#close-cart").addEventListener("click", closeCart);
cartBackdrop.addEventListener("click", closeCart);
document.querySelector("#start-shopping").addEventListener("click", () => {
  closeCart();
  document.querySelector("#shop").scrollIntoView({ behavior: "smooth" });
});

document.addEventListener("keydown", (event) => {
  if (event.key !== "Escape") return;
  if (!checkoutBackdrop.hidden) closeCheckout();
  else if (cartDrawer.classList.contains("open")) closeCart();
});

document.querySelector("#checkout-button").addEventListener("click", () => {
  openCheckout();
});

document.querySelector("#close-checkout").addEventListener("click", closeCheckout);
checkoutBackdrop.addEventListener("click", (event) => {
  if (event.target === checkoutBackdrop) closeCheckout();
});

checkoutForm.addEventListener("change", (event) => {
  if (event.target.name !== "paymentMethod") return;
  const onlineSelected = event.target.value === "online";
  paymentNote.textContent = onlineSelected
    ? "Online payment is not available yet because a payment gateway has not been connected. Choose cash on delivery to send an order request."
    : "Your order request will open in your email app. Payment is due on delivery.";
});

checkoutForm.addEventListener("submit", (event) => {
  event.preventDefault();
  const formData = new FormData(checkoutForm);
  if (formData.get("paymentMethod") === "online") {
    showToast("Online payments need a payment gateway. Choose cash on delivery for now.");
    return;
  }

  const orderLines = products
    .filter((product) => cart.has(product.id))
    .map((product) => `${cart.get(product.id)} × ${product.name} — ${formatPrice(product.price * cart.get(product.id))}`);
  const subtotal = products.reduce((total, product) => total + product.price * (cart.get(product.id) || 0), 0);
  const orderDetails = [
    "Sahani Family Business order request",
    "",
    `Name: ${formData.get("customerName")}`,
    `Phone: ${formData.get("phone")}`,
    `Delivery address: ${formData.get("address")}`,
    "Payment: Cash on delivery",
    "",
    "Items:",
    ...orderLines,
    "",
    `Subtotal: ${formatPrice(subtotal)}`,
    "Delivery and taxes to be confirmed."
  ].join("\n");
  const subject = encodeURIComponent("Sahani grocery order request");
  sendOrderEmail.href = `mailto:hello@sahanigroceries.com?subject=${subject}&body=${encodeURIComponent(orderDetails)}`;
  sendOrderEmail.hidden = false;
  orderRequestMessage.textContent = "Your order request is ready. Open your email app and send the message to confirm your order.";
  orderRequestMessage.hidden = false;
  checkoutForm.querySelector('[type="submit"]').hidden = true;
});

document.querySelector("#newsletter-form").addEventListener("submit", (event) => {
  event.preventDefault();
  showToast("Thanks for your interest! Newsletter sign-up isn't connected yet.");
  event.currentTarget.reset();
});
