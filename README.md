# README

アプリケーションを完成させようの課題です。
<% @books.each do |book| %>
  <div class="index-title">
   <p class="title">Title</p>
   <%= book.title %>
  </div>
  <p class="body">Body</p>
   <%= book.body %>
  <%= link_to "show", book_path(book.id) %>
 <% end %>
