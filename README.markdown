# Ray

_Minimal possible Ray primitive_

## Introduction

## Installation

````
npm install ray
````

## Usage

## Examples

TODO

## APIs

### Ray

#### <span class="heading">constructor</span> `(positions, direction, dimensions = 3)`

`position` A point in space representing the start of the ray.

`direction` A vector representing the direction the ray points towards.

`dimensions` the number of dimensions of space the ray exists within.

Constructs a new Ray primitive with the specified parameters.

#### <span class="heading">getMajorAxis</span> `()`

Returns the 0-based index of the ray's direction vector with the greatest magnitude.

#### <span class="heading">toRaySegment</span> `()`

Returns a RaySegment - the line segment created by `minT` to `maxT` along the ray.