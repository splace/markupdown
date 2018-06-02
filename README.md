# markupdown

//
// **VKFLAGS(3) MANUAL PAGE**
//
// **NAME**
//
// VkFlags - Vulkan bitmasks
//
// **C Specification**
//
// A collection of flags is represented by a bitmask using the type `VkFlags` :
//
//     `typedef uint32_t VkFlags;`
//
// **Description**
//
// Bitmasks are passed to many commands and structures to compactly represent options, but `VkFlags` is not used directly in the API. Instead, a `Vk*Flags` type which is an alias of `VkFlags` , and whose name matches the corresponding `Vk*FlagBits` that are valid for that type, is used.
//
// **See Also**VkColorComponentFlags.html
//
// **Document Notes**
//
// For more information, see the Vulkan Specification at URLhttps://www.khronos.org/registry/vulkan/specs/1.1-extensions/html/vkspec.html#VkFlags
//
// This page is extracted from the Vulkan Specification. Fixes and changes should be made to the Specification, not directly.
//
// **Copyright**
//
// Copyright (c) 2014-2018 Khronos Group. This work is licensed under ahttp://creativecommons.org/licenses/by/4.0/ .
//
// Version 1.1.76
//
//  Last updated 2018-05-25 04:00:58 PDT
