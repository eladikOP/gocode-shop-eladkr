<script lang="ts">
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <nav class="product-filter">
    <h1>Jackets</h1>

    <div class="sort">
      <div class="collection-sort">
        <label>Filter by:</label>
        <select>
          <option value="/">All Jackets</option>
          <option value="/">2016</option>
          <option value="/">jacket</option>
          <option value="/">Jackets</option>
          <option value="/">layers</option>
          <option value="/">Obermeyer</option>
          <option value="/">Roxy</option>
          <option value="/">womens</option>
        </select>
      </div>

      <div class="collection-sort">
        <label>Sort by:</label>
        <select>
          <option value="/">Featured</option>
          <option value="/">Best Selling</option>
          <option value="/">Alphabetically, A-Z</option>
          <option value="/">Alphabetically, Z-A</option>
          <option value="/">Price, low to high</option>
          <option value="/">Price, high to low</option>
          <option value="/">Date, new to old</option>
          <option value="/">Date, old to new</option>
        </select>
      </div>
    </div>
  </nav>
</template>

<style>
/* Product Layout */

.product-filter {
  display: flex;
  padding: 30px 0;
}

.sort {
  display: flex;
  align-self: flex-end;
}

.collection-sort {
  display: flex;
  flex-direction: column;
}

.collection-sort:first-child {
  padding-right: 20px;
}

label {
  color: #666;
  font-size: 10px;
  font-weight: 500;
  line-height: 2em;
  text-transform: uppercase;
}
@media (max-width: 480px) {
  h1 {
    margin-bottom: 20px;
  }

  .product-filter {
    flex-direction: column;
  }

  .sort {
    align-self: flex-start;
  }
}
</style>
