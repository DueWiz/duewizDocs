## Bootstrap Form

This gem is for generating bootstrap forms from the built in form helper and  already referred in the Gemfile.

`gem 'bootstrap_form'`

## Usage

Modify `form_for` to `bootstrap_form_for`

And if custom bootstrap class(CSS class) is needed, use the `class` attribute in the form helper.

Example:

```
<%= bootstrap_form_for(resource, as: resource_name, url: session_path(resource_name)) do |f| %>
    <h3 class="form-signin-heading">Login</h3>
    <%= f.email_field :email, autofocus: true %>
    <%= f.password_field :password, autocomplete: "off" %>
    <% if devise_mapping.rememberable? -%>
        <%= f.check_box :remember_me %>
    <% end -%>

    <div class="actions">
      <%= f.submit "Log in", class: "btn-lg btn-primary btn-block"%>
    </div>
    <br/>
    <%= render "users/shared/links" %>
<% end %>
```
I used `bootstrap_form_for` and customed `class` for the submit button.
