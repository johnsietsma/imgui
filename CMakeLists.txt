cmake_minimum_required(VERSION 2.6 FATAL_ERROR)

project(imgui)

add_library(imgui
	imconfig.h
	imgui.h
	imgui_internal.h
	stb_rect_pack.h
	stb_textedit.h
	stb_truetype.h

	imgui.cpp
	#imgui_demo.cpp
	imgui_draw.cpp
)
