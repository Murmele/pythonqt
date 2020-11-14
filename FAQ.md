# FAQ for pythonqt

## Why the generator is needed?
The generator is needed so that python knows how to handle the object, which method it has and so on.

## Why PyObjToQVariant parameter type is not a pointer?
Not needed, because QVariant::type() exists, with which the type is already stored in the QVariant
