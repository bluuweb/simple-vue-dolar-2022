<script setup></script>
<template>
    <nav class="text-gray-100 bg-gray-700">
        <div
            class="container flex items-center justify-between px-4 py-4 mx-auto"
        >
            <p>Logo API Dolar</p>
            <div class="flex items-center gap-2">
                <span
                    class="text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Dark/Light Mode</span
                >
                <label
                    for="default-toggle"
                    class="relative inline-flex items-center cursor-pointer"
                >
                    <input
                        type="checkbox"
                        value=""
                        id="default-toggle"
                        class="sr-only peer"
                    />
                    <div
                        class="w-11 h-6 bg-gray-200 rounded-full peer peer-focus:ring-4 peer-focus:ring-gray-300 dark:peer-focus:ring-gray-800 dark:bg-gray-800 peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:left-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-gray-800"
                    ></div>
                </label>
            </div>
        </div>
    </nav>
</template>
