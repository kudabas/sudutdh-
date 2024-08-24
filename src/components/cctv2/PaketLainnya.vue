<template>
     <div class="tabs">
        <div class="flex border-b border-gray-200">
            <button v-for="(tab, index) in tabs" :key="index" @click="activeTab = index"
                :class="{ 'border-b-2': activeTab === index, 'border-transparent': activeTab !== index }"
                class="px-4 py-2 mr-4 transition duration-500 ease-in-out hover:text-gray-700 focus:outline-none">
                {{ tab }}
            </button>
        </div>
        <div class="mt-4">
            <div v-show="activeTab === index" v-for="(content, index) in tabContents" :key="index">
                {{ content }}
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            activeTab: 0,
            tabs: ['Tab 1', 'Tab 2', 'Tab 3', 'Tab 4'],
            tabContents: ['Tab 1 Content yoman ', 'Tab 2 Content', 'Tab 3 Content', 'eusi']
        };
    }
};
</script>

<style scoped>
.tabs {
    max-width: 600px;
    margin: 0 auto;
}

.tabs button {
    color: #4a5568;
}

.tabs button.border-b-2 {
    border-color: #4a5568;
}

.tabs button.hover:text-gray-700 {
    color: #4a5568;
}
</style>

