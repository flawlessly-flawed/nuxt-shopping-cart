<template>

  <div class="cart-page">
    <p class="text-10xl font-serif mb-10 text-black;" style="color:black; text-align: center; font-size:50px; font-family:cursive;">Shop for items of your choice</p>
    <div class="top-row flex justify-around flex-wrap">
      <div class="cart-item px-4 mb-8 w-full sm:w-1/2 md:w-1/3 lg:w-1/3 xl:w-1/3">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5uhZQTUfFx3x0cTx160Iqe3r13_kosawS-w&usqp=CAU" alt="Item 1" class="w-full">
        <div class="item-details">
            <div class="left-items">
          <h2 class="text-lg font-bold mt-0">Item 1</h2>
          <p class="text-gray-600 p-2px mt-0">$25.00</p>
          </div>
          <div class="buy-now">
            <button>order now</button>
          </div>
        </div>
      </div>
      <div class="cart-item px-4 mb-8 w-full sm:w-1/2 md:w-1/3 lg:w-1/3 xl:w-1/3">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5uhZQTUfFx3x0cTx160Iqe3r13_kosawS-w&usqp=CAU" alt="Item 2" class="w-full">
         <div class="item-details">
            <div class="left-items">
          <h2 class="text-lg font-bold mt-0">Item 2</h2>
          <p class="text-gray-600 p-2px mt-0">$45.00</p>
          </div>
          <div class="buy-now">
            <button>order now</button>
          </div>
        </div>
      </div>
      <div class="cart-item px-4 mb-8 w-full sm:w-1/2 md:w-1/3 lg:w-1/3 xl:w-1/3">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5uhZQTUfFx3x0cTx160Iqe3r13_kosawS-w&usqp=CAU" alt="Item 3" class="w-full">
         <div class="item-details">
            <div class="left-items">
          <h2 class="text-lg font-bold mt-0">Item 3</h2>
          <p class="text-gray-600 p-2px mt-0">$65.00</p>
          </div>
          <div class="buy-now">
            <button>order now</button>
          </div>
        </div>
      </div>
    </div>
    <div class="bottom-row flex flex-wrap justify-center -mx-4">
      <div class="cart-item px-4 mb-8 w-full sm:w-1/2 md:w-1/3 lg:w-1/3 xl:w-1/3">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5uhZQTUfFx3x0cTx160Iqe3r13_kosawS-w&usqp=CAU" alt="Item 4" class="w-full">
         <div class="item-details">
            <div class="left-items">
          <h2 class="text-lg font-bold mt-0">Item 4</h2>
          <p class="text-gray-600 p-2px mt-0">$35.00</p>
          </div>
          <div class="buy-now">
            <button>order now</button>
          </div>
        </div>
      </div>
      <div class="cart-item px-4 mb-8 w-full sm:w-1/2 md:w-1/3 lg:w-1/3 xl:w-1/3">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5uhZQTUfFx3x0cTx160Iqe3r13_kosawS-w&usqp=CAU" alt="Item 5" class="w-full">
         <div class="item-details">
            <div class="left-items">
          <h2 class="text-lg font-bold mt-0">Item 5</h2>
          <p class="text-gray-600 p-2px mt-0">$35.00</p>
          </div>
          <div class="buy-now">
            <button>order now</button>
          </div>
        </div>
      </div>
      <div class="cart-item px-4 mb-1 w-full sm:w-1/2 md:w-1/3 lg:w-1/3 xl:w-1/3">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5uhZQTUfFx3x0cTx160Iqe3r13_kosawS-w&usqp=CAU" alt="Item 6" class="w-full">
        <div class="item-details">
            <div class="left-items">
          <h2 class="text-lg font-bold mt-0">Item 6</h2>
          <p class="text-gray-600 p-2px mt-0">$35.00</p>
          </div>
          <div class="buy-now">
            <button>order now</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  
</template>

<style>
.top-row,
.bottom-row {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-wrap: wrap;
  padding-bottom: 50px;
}

.item-details{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.item-details p {
  margin: 0;
}

button{
    margin-top: 20px;
}
  </style>
