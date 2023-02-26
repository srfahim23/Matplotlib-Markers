# Matplotlib-Markers
# Markers
You can use the keyword argument marker to emphasize each point with a specified marker:

Example

Mark each point with a circle:

    import matplotlib.pyplot as plt
    import numpy as np

    ypoints = np.array([3, 8, 1, 10])

    plt.plot(ypoints, marker = 'o')
    plt.show()

Note:You can see the result in the top a picture i included

Example

Mark each point with a star:

    '''
    plt.plot(ypoints, marker = '*')

Note: You can see the result in the second once picture i included

# Marker Reference
You can choose any of these markers:

    Marker          Description

    'o'             Circle

    '*'             Star

    '.'             Point

    ','             Pixel

    'x'             X

    'X'             X (filed)

    '+'             Plus

    'p'             Plus (filed)

    's'             Square

    'D'             Diamond

    'd'             Diamond (thin)

    'p'             Pentagon

    'H'             Hexagon

    'h'             Hexagon

    'v'             Triangle Down

    '^'             Triangle Up

    '<'             Triangle Left

    '>'             Triangle Right

    '1'             Tri Down

    '2'             Tri up

    '3'             Tri Left

    '4'             Tri Right

    '|'             Vline

    '_'             Hline


# Format Strings fmt
You can use also use the shortcut string notation parameter to specify the marker.

This parameter is also called fmt, and is written with this syntax:

marker|Line|color

Example

Mark each point with a cirle:

    import matplotlib.pyplot as plt
    import numpy as np

    ypoints = np.array([3, 8, 1, 10])

    plt.plot(ypoints, 'o:r')
    plt.show()

Note: You can see the result in the third picture i added in the top secotr picture.

The marker value can be anything from the Marker Reference above. 

The line value can be one of the following:

# Line Reference

    Line Syntax         Description

        '_'             Solid line

        ':'              Dotted line

        '__'             Dashed line

        '_.'             Dashed/dotted line

Note: If you leave out line value in, the fmt parameter, no line will be plotted.

The short color value can be one of the following

# Color Reference

    Color Syntax            Description

        'r'                 Red

        'g'                 Green

        'b'                 Blue

        'c'                 Cyan

        'm'                 Magenta

        'y'                 Yellow

        'k'                 Black

        'w'                 White

# Marker Size
You can use the keyword argument markersize or the shorter version, ms to set the size of the markers:

Example

Set the size of the markers to 20:

    import matplotlib.pyplot as plt
    import numpy as np

    ypoints = np.array([3, 8, 1, 10])

    plt.plot(ypoints, marker, marker = 'o' ms = 20)
    plt.show()

Note: You can see the result on the top i added i included    

# Marker Color
You can use the keyword argument markeredgecolor or the shorted mec to set the color of the edge of the markers:

Example

Set the EDGE color to red:

    import matplotlib.pyplot as plt
    import numpy as np

    ypoints = np.array([3, 8, 1, 10])

    plt.plot(ypoints, marker = 'o' ms = 20, mec = 'r')
    plt.show()

Note: You can see the result in the top i added picture the name including 5 maybe.

You can use the keyword agument markerfacecolor or the shorter mfc to set the color inside edge of the markers:

Example 

Set the FACE color to red:

    import matplotlib.pyplot as plt
    import numpy as np

    ypoints = np.array([3, 8, 1, 10])

    plt.plot(ypoints, marker = 'o' , ms = 20, mfc = 'r')
    plot.show()

Note: You can see the result in the top i added picture name was maybe 6 numbers count.

Use both the mec and mfc arguments to color the entire marker:

Example

Set the color of both the edge and the face to red:

    import matplotlib.pyplot as plt
    import numpy as np

    ypoints = np.array([3, 8, 1, 10])

    plt.plot(ypoints, marker = 'o', ms = 20, mec = 'r', mfc = 'r')

Note you can see the result in the top i added picture count 7

You can also use Hexadecimal color values:

Example

Mark each point with a beautiful green color:

    '''
    plt.plot(ypoints, marker = 'o', ms = 20, mec = '#4CAF50', mfc = '#4CAF50')
    '''
Note: You can see the result in the top i added a picture count no. 8

Or any of the 140 supported color names.

Example 

Mark each point with the color named "hotping":

    '''
    plt.plot(ypoints, marker = 'o', ms = 20, mec = 'hotpink', mfc = 'hotpint')
    '''

Note: You can see the result in the top i added a picture no. 9


