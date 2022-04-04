<template>
  <container>
    <svg viewBox="0 0 600 258" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M25.3915 25.5912C41.4493 9.52557 63.2283 0.5 85.9375 0.5H428.438H514.062C536.772 0.5 558.551 9.52557 574.609 25.5912C590.666 41.6568 599.688 63.4464 599.688 86.1667V107.583V150.417V171.833C599.688 194.554 590.666 216.343 574.609 232.409C558.551 248.474 536.772 257.5 514.062 257.5H471.25C437.186 257.5 404.518 243.962 380.431 219.863C356.344 195.765 342.812 163.08 342.812 129C342.812 117.64 338.302 106.745 330.273 98.7123C322.244 90.6795 311.355 86.1667 300 86.1667C288.645 86.1667 277.756 90.6795 269.727 98.7123C261.698 106.745 257.188 117.64 257.188 129C257.188 163.08 243.656 195.765 219.569 219.863C195.482 243.962 162.814 257.5 128.75 257.5H85.9375C63.2283 257.5 41.4493 248.474 25.3915 232.409C9.33368 216.343 0.3125 194.554 0.3125 171.833V150.417V107.583V86.1667C0.3125 63.4464 9.33368 41.6568 25.3915 25.5912Z"
        fill="white"
        fill-opacity="0.75"
      />
    </svg>
    <h1>ismakingsomething.cool</h1>
    <h2>apply for a free domain</h2>
    <form action="mailto:ismakingsomething.cool+apply@outlook.com" enctype="text/plain" method="POST">
      <inputs
        ><input
          type="text"
          name="name"
          placeholder="your name (optional)"
        /><br />
        <input
          type="email"
          name="email"
          placeholder="your email (required, will be made public)"
          required
        /><br />
        <input
          type="text"
          placeholder="requested subdomain (required)"
          name="subdomain"
          required
        /><br />
        <input
          type="text"
          placeholder="Nameservers (required)"
          name="nameservers"
          required
        /><br />
      </inputs>
      <links>
        <a
          href="https://github.com/ismakingsomethingdotcool/dns"
          target="_blank"
          >request other records here ↗</a
        >
        <input type="submit" value="submit →" />
      </links>
    </form>
  </container>
</template>

