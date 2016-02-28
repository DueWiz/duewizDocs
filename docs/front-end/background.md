#Background

This page is for picking up the most fundamentals for building front end for Student Organizer.




##Get Started

Student Organizer is built on top of Rails 4 with bootstrap.

[https://getbootstrap.com/](https://getbootstrap.com/)

With bootswatch theme Cerulean.

[https://bootswatch.com/cerulean/](https://bootswatch.com/cerulean/)




##Frontend Gem file

<pre><code>#bootstrap series
gem 'bootstrap-sass', '~> 3.3.5'
# bootswatch theme for bootstrap
gem 'bootswatch-rails'
#date picker
gem 'bootstrap-datepicker-rails'
#font awesome icons
gem "font-awesome-rails"
</code></pre>




##Date picker plugin

We are now using bootstrap-datepicker package for the calendar.

But we may decide to develop a calendar that meets only our use.




##Fontawesome icon example
<code>&lt;i class=&quot;fa fa-cog&quot;&gt;&lt;/i&gt;</code>

This code snippet adds a settings like cog icon.

##Import to Rails

app/assets/javascripts/application.js

<pre><code>//= require bootstrap-datepicker</code></pre>

app/assets/stylesheets/application.css.scss

<pre><code>// Example using 'Cerulean' bootswatch

 //Import bootstrap-sprockets
 @import &quot;bootstrap-sprockets&quot;;

 // Import cerulean variables
 @import &quot;bootswatch/cerulean/variables&quot;;

 // Then bootstrap itself
 @import &quot;bootstrap&quot;;

 // Bootstrap body padding for fixed navbar
 body { padding-top: 60px; }

 // And finally bootswatch style itself
 @import &quot;bootswatch/cerulean/bootswatch&quot;;

// font awesome
 @import &quot;font-awesome&quot;;

//datepicker and customized css for datepicker
@import &quot;bootstrap-datepicker3&quot;;

@import &quot;datepicker&quot;;</code></pre>
