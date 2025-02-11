# LIDAR Terrain Flow Analysis

A comprehensive C application for analyzing LIDAR point cloud data and simulating water flow over terrain. This project processes high-resolution terrain data to identify potential water pooling areas and visualize water flow patterns in geographic regions.

## Features

- Point cloud data processing and analysis
- Water flow simulation over terrain
- Dynamic visualization system for terrain and water depth
- Logarithmic scaling for improved visualization
- Extensible data structures for large-scale data handling
- Bitmap manipulation for visualization output

## Core Components

### Point Cloud Analysis
- Processing of 1-meter resolution LIDAR data
- Height analysis and terrain mapping
- Efficient 2D array manipulation
- Custom expanding list data structure

### Water Flow Simulation
- Watershed algorithm implementation
- Configurable simulation parameters:
  - Water flow coefficient
  - Evaporation rate
  - Initial water levels
  - Iteration control
- Directional flow analysis (N,S,E,W)

### Visualization
- GIF image generation of terrain data
- Water depth visualization with blue shading
- Logarithmic scaling for better depth representation
- Sequential output capability for flow analysis

## Performance Considerations

- Optimized for large-scale point cloud datasets
- Efficient memory management for terrain data
- Balanced accuracy and computational efficiency
- Scalable data structures for varying terrain sizes

## Future Improvements

- Enhanced visualization options
- Multi-threading support for larger datasets
- Additional terrain analysis metrics
- Real-time visualization capabilities
- Integration with GIS systems

## License

MIT License

## Acknowledgments

- Bitmap handling functions from [wernsey/bitmap](https://github.com/wernsey/bitmap)

## File Availability

Because this was created as part of an assignment, the source files have been made private. Please contact me with inquiries.