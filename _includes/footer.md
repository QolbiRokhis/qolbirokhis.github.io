<footer class="p-8">
  <div class="container max-w-2xl mx-auto">
    <div class="mb-4">
      <ul class="flex flex-wrap leading-loose text-sm justify-center">
      {% for item in site.data.footer %}
        <li class="mr-4">
          <a
            href="{{item.url}}"
            class="hover:underline text-gray-600 no-underline hover:text-gray-800"
            target="_blank"
            >{{item.name}}</a
          >
        </li>
        {% endfor %}
      </ul>
    </div>
    <p class="leading-snug text-gray-600 text-xs text-center">
      © 2022 All rights reserved by
      <a href="http://github.com/QolbiRokhis" class="text-gray-600 hover:text-gray-800 no-underline hover:underline">Qolbi Rokhis</a>
    </p>
  </div>
</footer>
