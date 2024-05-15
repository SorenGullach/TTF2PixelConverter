# TTF2PixelConverter

This C# code defines two classes, `PixelDataCPP` and `PixelData`, within the `TTF2PixelConverter` namespace. These classes are designed to facilitate the conversion of TrueType fonts (TTF) into pixel data and provide functionalities for saving the pixel data as C++ header and source files.

The `PixelDataCPP` class encapsulates properties and methods related to pixel data manipulation and saving font information in C++ format. It includes properties for image dimensions, coordinates, bits per pixel, stride, and image data. Additionally, it provides methods for saving font information as C++ header files and constructing the content of the header file with appropriate licensing information and font item declarations.

The `PixelData` class inherits from `PixelDataCPP` and extends its functionality by implementing methods for filling image data from pixel data, generating string representations of pixel data, and saving pixel data lists to files. It includes private fields for storing pixel data, constants for bits per byte, and a constructor for initializing pixel data. The class also overrides the `ToString` method to provide a string representation of the pixel data and implements methods for filling image data from pixel data and saving pixel data lists to files.

Together, these classes offer a comprehensive solution for converting TrueType fonts into pixel data and saving the pixel data in C++ format, enabling seamless integration into C++ projects for embedded systems or other applications requiring pixel manipulation and rendering.

![App image](https://github.com/SorenGullach/TTF2PixelConverter/blob/master/Font%20app.png)
