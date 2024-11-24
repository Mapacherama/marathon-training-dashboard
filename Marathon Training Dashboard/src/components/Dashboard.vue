<template>
  <div class="min-h-screen bg-gray-100 p-6">
    <!-- Header -->
    <header class="bg-blue-600 text-white p-4 rounded-lg shadow">
      <h1 class="text-3xl font-bold">Marathon Training Dashboard</h1>
      <p class="text-sm mt-2">Track your progress, set goals, and stay motivated!</p>
    </header>

    <!-- Main Content -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-6">
      <!-- Card 1 -->
      <div class="bg-white p-4 rounded-lg shadow hover:shadow-lg transition">
        <h2 class="text-xl font-semibold text-gray-800">Upcoming Training</h2>
        <p class="text-gray-600 mt-2">View and plan your weekly training schedule.</p>
        <button class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-500">
          View Schedule
        </button>
      </div>

      <!-- Card 2 -->
      <div class="bg-white p-4 rounded-lg shadow hover:shadow-lg transition">
        <h2 class="text-xl font-semibold text-gray-800">Progress Tracker</h2>
        <p class="text-gray-600 mt-2">Monitor your pace, mileage, and goals.</p>
        <button class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-500">
          View Progress
        </button>
      </div>

      <!-- Card 3 -->
      <div class="bg-white p-4 rounded-lg shadow hover:shadow-lg transition">
        <h2 class="text-xl font-semibold text-gray-800">Photo Gallery</h2>
        <p class="text-gray-600 mt-2">Upload and browse your training moments.</p>
        <button class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-500">
          Open Gallery
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dashboard",
};
</script>

<style scoped>
/* You can add additional scoped styles here */
</style>
