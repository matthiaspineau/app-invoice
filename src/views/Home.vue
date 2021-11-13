<template>
  <div class="home">
    <div class="view">
      <!-- sidebar -->
      <sidebar></sidebar>

      <!-- content -->
      <div class="content">
        <div class="content-invoice">

          <header class="mt-5">
            <div class="d-flex">

              <div class="">
                <h5>incoices</h5>
                <small>There are 7 invoices</small>
              </div>

              <div class="flex-grow-1 ps-4 pe-4 text-end">
                <span>filter by</span>
                <span>
                  <svg width="11" height="7" xmlns="http://www.w3.org/2000/svg"><path d="M1 1l4.228 4.228L9.456 1" stroke="#7C5DFA" stroke-width="2" fill="none" fill-rule="evenodd"/></svg>
                </span>
              </div>

              <div class="">
                <span>
                  <svg width="11" height="11" xmlns="http://www.w3.org/2000/svg"><path d="M6.313 10.023v-3.71h3.71v-2.58h-3.71V.023h-2.58v3.71H.023v2.58h3.71v3.71z" fill="#7C5DFA" fill-rule="nonzero"/></svg>
                </span>
                <span>new invoice</span>
              </div>

            </div>
          </header>

          <main class="mt-3">

            <div class="invoice-item ps-2 pe-2 mt-2">
              <span>#RT3080</span>
              <span>Due  19 Aug 2021</span>
              <span>Jensen Huang</span>
              <span>£ 1,800.90</span>
              <span>Paid</span>
              <span>
                <svg width="7" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M1 1l4 4-4 4" stroke="#7C5DFA" stroke-width="2" fill="none" fill-rule="evenodd"/></svg>
              </span>
            </div>

            <div class="invoice-item ps-2 pe-2 mt-2">
              <span>#RT3080</span>
              <span>Due  19 Aug 2021</span>
              <span>Jensen Huang</span>
              <span>£ 1,800.90</span>
              <span>Paid</span>
              <span>
                <svg width="7" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M1 1l4 4-4 4" stroke="#7C5DFA" stroke-width="2" fill="none" fill-rule="evenodd"/></svg>
              </span>
            </div>

            <div class="invoice-item ps-2 pe-2 mt-2">
              <span>#RT3080</span>
              <span>Due  19 Aug 2021</span>
              <span>Jensen Huang</span>
              <span>£ 1,800.90</span>
              <span>Paid</span>
              <span>
                <svg width="7" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M1 1l4 4-4 4" stroke="#7C5DFA" stroke-width="2" fill="none" fill-rule="evenodd"/></svg>
              </span>
            </div>

          </main>


        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Sidebar from "../components/sidebar/Sidebar.vue";
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "Home",
  components: {
    Sidebar,
    // HelloWorld
  },
};
</script>
