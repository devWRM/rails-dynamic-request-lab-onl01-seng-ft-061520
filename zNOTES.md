












INCORRECT File:     views/students/show.html.erb

<!--
Tried but doesn't work:
<% @students.each do |student| %>
    <%= student.last_name %>
<% end %>

Tried but doesn't work:
<h1><%= student_path(@student) %></h1>

Called the .to_s method but it doesn't work:
<h1><%= @students.to_s %></h1>
-->


<h1><%= student_path(@student) %></h1>


