<script setup>

</script>

<template>
  <section class="app-container mx-auto px-4 py-10 space-y-[1.875rem] max-w-full">
    <article class="space-y-1.5">
      <h1 class="text-2xl font-medium">Billing</h1>
      <p class="text-sm text-secondary">Manage your billing and payment details</p>
    </article>
    <div class="space-y-3">
      <h5 class="font-medium text-secondary">Active Plan</h5>
      <!-- Table -->
      <div class="border border-soft-200 rounded-[0.625rem] bg-white flex items-center gap-4 py-5">
        <div class="overflow-x-auto grow">
          <div class="min-w-full inline-block align-middle">
            <table class="min-w-full whitespace-nowrap">
              <thead class="text-secondary font-medium text-sm">
                <tr>
                  <th class="px-5 text-start py-1">PLAN NAME</th>
                  <th class="px-5 text-start py-1">PLAN</th>
                  <th class="px-5 text-start py-1">COST</th>
                  <th class="px-5 text-start py-1">PURCHASE DATE</th>
                  <th class="px-5 text-start py-1">EXPIRY DATE</th>
                </tr>
              </thead>
              <tbody class="font-medium text-strong">
                <tr>
                  <td class="px-5 py-1">Business</td>
                  <td class="px-5 py-1">Yearly</td>
                  <td class="px-5 py-1">$198.00</td>
                  <td class="px-5 py-1">10 Aug 2025</td>
                  <td class="px-5 py-1">10 Aug 2026</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="px-5">
          <a href="#"
            class="text-primary-500 font-medium border border-primary-500 rounded-[0.625rem] px-3.25 py-2.5 whitespace-nowrap">
            Change Plan
          </a>
        </div>
      </div>
    </div>
    <div class="space-y-3">
      <h5 class="font-medium text-secondary">Purchase History</h5>
      <!-- Table -->
      <div class="border border-soft-200 bg-white flex gap-4 p-5 rounded-[0.625rem] overflow-x-auto">
        <div class="min-w-full inline-block align-middle">
          <table class="min-w-full whitespace-nowrap">
            <thead class="text-secondary font-medium text-sm">
              <tr class="rounded-lg">
                <th class="text-start px-5 py-4 bg-soft rounded-l-[0.625rem]">PLAN NAME</th>
                <th class="text-start px-5 py-4 bg-soft">PLAN</th>
                <th class="text-start px-5 py-4 bg-soft">COST</th>
                <th class="text-start px-5 py-4 bg-soft">PURCHASE DATE</th>
                <th class="text-start px-5 py-4 bg-soft">EXPIRY DATE</th>
                <th class="text-start px-5 py-4 bg-soft rounded-r-[0.625rem]">STATUS</th>
              </tr>
            </thead>
            <tbody class="font-medium text-sm text-strong divide-y divide-border-light">
              <tr>
                <td class="p-4">Business</td>
                <td class="p-4">Yearly</td>
                <td class="p-4">$198.00</td>
                <td class="p-4">10 Aug 2025</td>
                <td class="p-4">10 Aug 2026</td>
                <td class="p-4">Active</td>
              </tr>
              <tr>
                <td class="p-4">Business</td>
                <td class="p-4">Starter</td>
                <td class="p-4">$198.00</td>
                <td class="p-4">27 Dec 2022</td>
                <td class="p-4">27 Dec 2022</td>
                <td class="p-4">Expired</td>
              </tr>
              <tr>
                <td class="p-4">Business</td>
                <td class="p-4">Monthly</td>
                <td class="p-4">$198.00</td>
                <td class="p-4">27 Dec 2022</td>
                <td class="p-4">27 Dec 2022</td>
                <td class="p-4">Expired</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
