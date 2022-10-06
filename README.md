# perfil

This is a backup to https://github.com/estrellacristo/cvrepositorio.github.io

Estoy tratando de hacer funcionar para build y deploy to published in jenkins github

este es el error con Lazyload

Run actions/jekyll-build-pages@v1
/usr/bin/docker run --name ghcrioactionsjekyllbuildpagesv104_148f03 --label 5364e3 --workdir /github/workspace --rm -e "GITHUB_PAGES" -e "INPUT_SOURCE" -e "INPUT_DESTINATION" -e "INPUT_FUTURE" -e "INPUT_BUILD_REVISION" -e "INPUT_VERBOSE" -e "INPUT_TOKEN" -e "HOME" -e "GITHUB_JOB" -e "GITHUB_REF" -e "GITHUB_SHA" -e "GITHUB_REPOSITORY" -e "GITHUB_REPOSITORY_OWNER" -e "GITHUB_RUN_ID" -e "GITHUB_RUN_NUMBER" -e "GITHUB_RETENTION_DAYS" -e "GITHUB_RUN_ATTEMPT" -e "GITHUB_ACTOR" -e "GITHUB_TRIGGERING_ACTOR" -e "GITHUB_WORKFLOW" -e "GITHUB_HEAD_REF" -e "GITHUB_BASE_REF" -e "GITHUB_EVENT_NAME" -e "GITHUB_SERVER_URL" -e "GITHUB_API_URL" -e "GITHUB_GRAPHQL_URL" -e "GITHUB_REF_NAME" -e "GITHUB_REF_PROTECTED" -e "GITHUB_REF_TYPE" -e "GITHUB_WORKSPACE" -e "GITHUB_ACTION" -e "GITHUB_EVENT_PATH" -e "GITHUB_ACTION_REPOSITORY" -e "GITHUB_ACTION_REF" -e "GITHUB_PATH" -e "GITHUB_ENV" -e "GITHUB_STEP_SUMMARY" -e "GITHUB_STATE" -e "GITHUB_OUTPUT" -e "RUNNER_OS" -e "RUNNER_ARCH" -e "RUNNER_NAME" -e "RUNNER_TOOL_CACHE" -e "RUNNER_TEMP" -e "RUNNER_WORKSPACE" -e "ACTIONS_RUNTIME_URL" -e "ACTIONS_RUNTIME_TOKEN" -e "ACTIONS_CACHE_URL" -e "ACTIONS_ID_TOKEN_REQUEST_URL" -e "ACTIONS_ID_TOKEN_REQUEST_TOKEN" -e GITHUB_ACTIONS=true -e CI=true -v "/var/run/docker.sock":"/var/run/docker.sock" -v "/home/runner/work/_temp/_github_home":"/github/home" -v "/home/runner/work/_temp/_github_workflow":"/github/workflow" -v "/home/runner/work/_temp/_runner_file_commands":"/github/file_commands" -v "/home/runner/work/perfil/perfil":"/github/workspace" ghcr.io/actions/jekyll-build-pages:v1.0.4
Configuration file: none
  Logging at level: debug
      GitHub Pages: github-pages v227
      GitHub Pages: jekyll v3.9.2
             Theme: jekyll-theme-primer
      Theme source: /usr/local/bundle/gems/jekyll-theme-primer-0.6.0
         Requiring: jekyll-github-metadata
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
    Liquid Warning: Liquid syntax error (line 16): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
    Liquid Warning: Liquid syntax error (line 48): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
    Liquid Warning: Liquid syntax error (line 65): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
    Liquid Warning: Liquid syntax error (line 130): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
    Liquid Warning: Liquid syntax error (line 1): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
    Liquid Warning: Liquid syntax error (line 29): Unexpected character # in "{{#each classes}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
    Liquid Warning: Liquid syntax error (line 38): Unexpected character / in "{{/each}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
    Liquid Warning: Liquid syntax error (line 46): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
    Liquid Warning: Liquid syntax error (line 1): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 70): Unexpected character # in "{{#each events}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 73): Unexpected character # in "{{#each events}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 76): Unexpected character # in "{{#isnt callback undefined}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 76): Unexpected character / in "{{/isnt}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 76): Unexpected character # in "{{#isnt param undefined}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 76): Unexpected character / in "{{/isnt}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 81): Unexpected character / in "{{/each}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 83): Unexpected character / in "{{/each}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 85): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
    Liquid Warning: Liquid syntax error (line 1): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
    Liquid Warning: Liquid syntax error (line 7): Unexpected character # in "{{#each options}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
    Liquid Warning: Liquid syntax error (line 16): Unexpected character / in "{{/each}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
    Liquid Warning: Liquid syntax error (line 22): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
    Liquid Warning: Liquid syntax error (line 16): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoheight.hbs
    Liquid Warning: Liquid syntax error (line 41): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoheight.hbs
    Liquid Warning: Liquid syntax error (line 17): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoplay.hbs
    Liquid Warning: Liquid syntax error (line 51): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoplay.hbs
    Liquid Warning: Liquid syntax error (line 18): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autowidth.hbs
    Liquid Warning: Liquid syntax error (line 52): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autowidth.hbs
    Liquid Warning: Liquid syntax error (line 16): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/basic.hbs
    Liquid Warning: Liquid syntax error (line 58): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/basic.hbs
    Liquid Warning: Liquid syntax error (line 1): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
    Liquid Warning: Liquid syntax error (line 3): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
    Liquid Warning: Liquid syntax error (line 21): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
    Liquid Warning: Liquid syntax error (line 23): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
    Liquid Warning: Liquid syntax error (line 41): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
    Liquid Warning: Liquid syntax error (line 77): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
    Liquid Warning: Liquid syntax error (line 1): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 5): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 9): Unexpected character # in "{{#each tags}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 10): Unexpected character # in "{{#is tag "core"}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 11): Unexpected character # in "{{#withSort pages "data.sort"}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 17): Unexpected character / in "{{/withSort}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 18): Unexpected character / in "{{/is}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 19): Unexpected character / in "{{/each}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 23): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 27): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 31): Unexpected character # in "{{#each tags}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 32): Unexpected character # in "{{#is tag "plugin"}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 33): Unexpected character # in "{{#withSort pages "data.sort"}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 39): Unexpected character / in "{{/withSort}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 40): Unexpected character / in "{{/is}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 41): Unexpected character / in "{{/each}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 45): Unexpected character # in "{{#markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 49): Unexpected character / in "{{/markdown }}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 53): Unexpected character # in "{{#each tags}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 54): Unexpected character # in "{{#is tag "external"}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 55): Unexpected character # in "{{#withSort pages "data.sort"}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 61): Unexpected character / in "{{/withSort}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 62): Unexpected character / in "{{/is}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
    Liquid Warning: Liquid syntax error (line 63): Unexpected character / in "{{/each}}" in assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
  Liquid Exception: Liquid syntax error (line 35): Variable '{{!-- ## owl.lazyload.js LazyLoad require `class="owl-lazy"` and link to image inside data: data-src="url_to_img" or/and data-src-retina="url_to_highres_img". There is also option to load images into background but this needs to be tested. [See demo](/demos/demo.html) Usage: ``` $('.owl-carousel').owlCarousel({ lazyLoad:true }' was not properly terminated with regexp: /\}\}/ in assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/dev-buildin-plugins.hbs
/usr/local/bundle/gems/liquid-4.0.3/lib/liquid/block_body.rb:136:in `raise_missing_variable_terminator': Liquid syntax error (line 35): Variable '{{!-- (Liquid::SyntaxError)

## owl.lazyload.js

LazyLoad require `class="owl-lazy"` and link to image inside data: data-src="url_to_img" or/and data-src-retina="url_to_highres_img".
There is also option to load images into background but this needs to be tested. [See demo](/demos/demo.html)

Usage:

```
$('.owl-carousel').owlCarousel({
	lazyLoad:true
}' was not properly terminated with regexp: /\\}\\}/
	from /usr/local/bundle/gems/liquid-4.0.3/lib/liquid/block_body.rb:128:in `create_variable'
	from /usr/local/bundle/gems/liquid-4.0.3/lib/liquid/block_body.rb:39:in `parse'
	from /usr/local/bundle/gems/liquid-4.0.3/lib/liquid/document.rb:10:in `parse'
	from /usr/local/bundle/gems/liquid-4.0.3/lib/liquid/document.rb:5:in `parse'
	from /usr/local/bundle/gems/liquid-4.0.3/lib/liquid/template.rb:132:in `parse'
	from /usr/local/bundle/gems/liquid-4.0.3/lib/liquid/template.rb:116:in `parse'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/liquid_renderer/file.rb:13:in `block in parse'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/liquid_renderer/file.rb:49:in `measure_time'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/liquid_renderer/file.rb:12:in `parse'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/renderer.rb:121:in `render_liquid'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/renderer.rb:79:in `render_document'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/renderer.rb:62:in `run'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/site.rb:479:in `render_regenerated'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/site.rb:472:in `block in render_pages'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/site.rb:471:in `each'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/site.rb:471:in `render_pages'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/site.rb:192:in `render'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/site.rb:71:in `process'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/command.rb:28:in `process_site'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/commands/build.rb:65:in `build'
	from /usr/local/bundle/gems/jekyll-3.9.2/lib/jekyll/commands/build.rb:36:in `process'
	from /usr/local/bundle/gems/github-pages-227/bin/github-pages:70:in `block (3 levels) in <top (required)>'
	from /usr/local/bundle/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute'
	from /usr/local/bundle/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each'
	from /usr/local/bundle/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute'
	from /usr/local/bundle/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go'
	from /usr/local/bundle/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program'
	from /usr/local/bundle/gems/github-pages-227/bin/github-pages:6:in `<top (required)>'
	from /usr/local/bundle/bin/github-pages:23:in `load'
	from /usr/local/bundle/bin/github-pages:23:in `<main>'
         Requiring: jekyll-seo-tag
         Requiring: jekyll-coffeescript
         Requiring: jekyll-commonmark-ghpages
         Requiring: jekyll-gist
         Requiring: jekyll-github-metadata
         Requiring: jekyll-paginate
         Requiring: jekyll-relative-links
         Requiring: jekyll-optional-front-matter
         Requiring: jekyll-readme-index
         Requiring: jekyll-default-layout
         Requiring: jekyll-titles-from-headings
   GitHub Metadata: Initializing...
            Source: /github/workspace/./
       Destination: /github/workspace/./_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
        Generating: JekyllOptionalFrontMatter::Generator finished in 0.00829104 seconds.
        Generating: JekyllReadmeIndex::Generator finished in 0.128334718 seconds.
        Generating: Jekyll::Paginate::Pagination finished in 5.9e-06 seconds.
   GitHub Metadata: Generating for estrellacristo/perfil
   GitHub Metadata: Calling @client.pages("estrellacristo/perfil", {})
        Generating: JekyllRelativeLinks::Generator finished in 0.436036799 seconds.
        Generating: JekyllDefaultLayout::Generator finished in 0.001563508 seconds.
         Requiring: kramdown-parser-gfm
        Generating: JekyllTitlesFromHeadings::Generator finished in 0.031412651 seconds.
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/animate.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-classes.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-events.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/api-options.hbs
         Rendering: assets/vendors/general/jquery-form/docs/api.md
  Pre-Render Hooks: assets/vendors/general/jquery-form/docs/api.md
  Rendering Markup: assets/vendors/general/jquery-form/docs/api.md
  Rendering Layout: assets/vendors/general/jquery-form/docs/api.md
     Layout source: theme
   GitHub Metadata: Calling @client.repository("estrellacristo/perfil", {:accept=>"application/vnd.github.drax-preview+json"})
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoheight.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoheight.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoheight.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoheight.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoheight.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoplay.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoplay.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoplay.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoplay.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autoplay.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autowidth.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autowidth.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autowidth.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autowidth.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/autowidth.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/basic.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/basic.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/basic.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/basic.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/basic.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/center.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
  Rendering Markup: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
  Rendering Layout: assets/vendors/general/owl.carousel/docs_src/templates/pages/demos/demos.hbs
         Rendering: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/dev-buildin-plugins.hbs
  Pre-Render Hooks: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/dev-buildin-plugins.hbs
  Rendering Liquid: assets/vendors/general/owl.carousel/docs_src/templates/pages/docs/dev-buildin-plugins.hbs
github-pages 227 | Error:  Liquid syntax error (line 35): Variable '{{!--

## owl.lazyload.js

LazyLoad require `class="owl-lazy"` and link to image inside data: data-src="url_to_img" or/and data-src-retina="url_to_highres_img".
There is also option to load images into background but this needs to be tested. [See demo](/demos/demo.html)

Usage:

```
$('.owl-carousel').owlCarousel({
	lazyLoad:true
}' was not properly terminated with regexp: /\}\}/
