<template>
<main class="wrapper">
    <h1>Past Orders</h1>

    <table class="product-table">
      <thead class ="titles">
        <tr>
          <td>Product</td>
          <td>Price</td>
          <td>Quantity</td>
          <td>Total</td>
          <td><span class="sr-only">Actions</span></td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Carrot</td>
          <td>$2.75</td>
          <td>4</td>
          <td>$11.00</td>
          <td><button class="btn btn-dark">Add</button></td>
        </tr>
        <tr>
          <td>Orange</td>
          <td>$4.95</td>
          <td>5</td>
          <td>$24.75</td>
          <td><button class="btn btn-dark">Add</button></td>
        </tr>
      </tbody>
    </table>
  </main>
</template>
