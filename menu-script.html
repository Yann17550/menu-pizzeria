<script>
// Données hardcodées (plus tard remplacées par Google Sheets)
const menuData = {
  pizzas: [
    { id: 'reine', emoji: '👑', nom: 'Reine', prix: '12€' },
    { id: 'margherita', emoji: '🍅', nom: 'Margherita', prix: '11€' },
    { id: '4saisons', emoji: '🌿', nom: '4 Saisons', prix: '13.50€' },
    { id: 'calzone', emoji: '🌯', nom: 'Calzone', prix: '14€' }
  ],
  boissons: [
    { id: 'coca', emoji: '🥤', nom: 'Coca Cola', prix: '3€' },
    { id: 'eau', emoji: '💧', nom: 'Eau plate', prix: '2.50€' },
    { id: 'biere', emoji: '🍺', nom: 'Bière pression', prix: '4€' }
  ],
  desserts: [
    { id: 'tiramisu', emoji: '☕', nom: 'Tiramisu', prix: '6€' },
    { id: 'glace', emoji: '🍨', nom: 'Glace vanille', prix: '4.50€' },
    { id: 'fondant', emoji: '🍫', nom: 'Fondant chocolat', prix: '6.50€' }
  ]
};

// Initialisation au chargement
document.addEventListener('DOMContentLoaded', function() {
  initTabs();
  initMenuItems();
});

// Gestion onglets
function initTabs() {
  const tabBtns = document.querySelectorAll('.tab-btn');
  const categories = document.querySelectorAll('.category');
  
  tabBtns.forEach(btn => {
    btn.addEventListener('click', function() {
      const category = this.dataset.category;
      
      // Active l'onglet
      tabBtns.forEach(b => b.classList.remove('active'));
      this.classList.add('active');
      
      // Affiche la catégorie
      categories.forEach(cat => cat.classList.remove('active'));
      document.getElementById(category).classList.add('active');
      
      console.log(`Catégorie sélectionnée: ${category}`);
    });
  });
}

// Gestion sélection articles
function initMenuItems() {
  const items = document.querySelectorAll('.menu-item');
  
  items.forEach(item => {
    item.addEventListener('click', function(e) {
      e.stopPropagation();
      
      // Toggle sélection
      this.classList.toggle('selected');
      
      const itemId = this.dataset.item;
      const estSelectionne = this.classList.contains('selected');
      
      if (estSelectionne) {
        console.log(`✅ AJOUT: ${itemId}`);
        alert(`Ajouté: ${itemId.toUpperCase()} !`);
      } else {
        console.log(`❌ RETIRÉ: ${itemId}`);
        alert(`Retiré: ${itemId.toUpperCase()}`);
      }
    });
    
    // Support tactile double-tap pour désélection rapide
    let tapCount = 0;
    item.addEventListener('touchend', function() {
      tapCount++;
      setTimeout(() => tapCount = 0, 300);
      
      if (tapCount === 2) {
        this.classList.remove('selected');
        console.log(`🚫 Double-tap: ${this.dataset.item} désélectionné`);
      }
    });
  });
}

// Fonction pour vider toutes les sélections (bonus)
function viderSelection() {
  document.querySelectorAll('.menu-item.selected').forEach(item => {
    item.classList.remove('selected');
  });
  console.log('🗑️ Panier vidé');
}

// Raccourci clavier (Espace = vider)
document.addEventListener('keydown', function(e) {
  if (e.code === 'Space') {
    e.preventDefault();
    viderSelection();
  }
});
</script>
