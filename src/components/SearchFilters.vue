<template>
  <section class="bg-gray-800">
    <div class="flex justify-between px-4 py-3">
      <div class="relative">
        <div class="absolute inset-y-0 left-0 flex items-center pl-3">
          <svg
            class="h-6 w-6 fill-current text-gray-600"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M16.32 14.9l1.1 1.1c.4-.02.83.13 1.14.44l3 3a1.5 1.5 0 0 1-2.12 2.12l-3-3a1.5 1.5 0 0 1-.44-1.14l-1.1-1.1a8 8 0 1 1 1.41-1.41l.01-.01zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"
            />
          </svg>
        </div>
        <input
          class="block w-full bg-gray-900 focus:outline-none focus:bg-white focus:text-gray-900 text-white rounded-lg pl-10 pr-4 py-2"
          placeholder="Search by keywords"
        />
      </div>
      <button
        class="inline-flex bg-gray-700 hover:bg-gray-600 focus:outline-none focus:shadow-outline rounded-lg shadow pl-3 pr-4"
      >
        <svg class="h-6 w-6 fill-current text-gray-500" viewBox="0 0 24 24">
          <path
            d="M3 6a1 1 0 0 1 1-1h16a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1zm3 6a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1zm4 5a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2h-4z"
          />
        </svg>
        <span class="ml-1 text-white font-medium">Filters</span>
      </button>
    </div>
    <form>
      <fieldset>
        <div>
          <label>
            <span>Bedrooms</span>
            <select>
              <option>4</option>
            </select>
          </label>
          <label>
            <span>Bathrooms</span>
            <select>
              <option>2</option>
            </select>
          </label>
        </div>
        <div>
          <label>
            <span>Price Range</span>
            <select>
              <option>Up to $2,000 /wk</option>
            </select>
          </label>
        </div>
      </fieldset>
      <fieldset>
        <legend>Property Type</legend>
        <label>
          <input type="radio" name="propertyType" value="house" />
          House
        </label>
        <label>
          <input type="radio" name="propertyType" value="house" />
          Apartment
        </label>
        <label>
          <input type="radio" name="propertyType" value="house" />
          Loft
        </label>
        <label>
          <input type="radio" name="propertyType" value="house" />
          Townhouse
        </label>
      </fieldset>
      <fieldset>
        <legend>Amenities</legend>
        <label>
          <input type="checkbox" name="balcony" />
          Balcony
        </label>
        <label>
          <input type="checkbox" name="airConditioning" />
          Air conditioning
        </label>
        <label>
          <input type="checkbox" name="pool" />
          Pool
        </label>
        <label>
          <input type="checkbox" name="beach" />
          Beach
        </label>
        <label>
          <input type="checkbox" name="petFriendly" value="house" />
          Pet friendly
        </label>
        <label>
          <input type="checkbox" name="kidFriendly" value="house" />
          Kid friendly
        </label>
      </fieldset>
      <div>
        <button>Update filters</button>
      </div>
    </form>
  </section>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
</style>