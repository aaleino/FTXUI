function(example name)
  add_executable(${name} ${name}.cpp)
  target_link_libraries(${name} PUBLIC dom)
  set_property(TARGET ${name} PROPERTY CXX_STANDARD 17)
endfunction(example)

example(border)
example(color_gallery)
example(dbox)
example(gauge)
example(graph)
example(hflow)
example(html_like)
example(package_manager)
example(paragraph)
example(separator)
example(size)
example(spinner)
example(style_blink)
example(style_bold)
example(style_color)
example(color_truecolor_RGB)
example(color_truecolor_HSV)
example(color_info_palette256)
example(style_dim)
example(style_gallery)
example(style_inverted)
example(style_underlined)
example(vbox_hbox)
example(window)
