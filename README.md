# is_even
> Return true if the number passed is even, hopefully...

## Install
requires gcc to work
```
git clone https://github.com/brushwayne/is_even
cd is_even
gcc is_even.c -o is_even
./is_even <number>
```

## About
This is a 100% serious project inspired from [@samuelmarina/is-odd](https://www.npmjs.com/package/@samuelmarina/is-odd), and it is made to help the community.

The problem still lies, that we need to figure out if a number is even or not. The go to way for it earlier has been evaluating if-else statements which tend to be a lot slower because of the huge number of assembly instructions generated.

The approach we take here surpasses both if-else and modulo operation checking, as modulo is a heavy weight floating point operation. here, instead of doing these idiotic things, we use the compiler optimization of switch cases to theoretically do the computation in O(1) time, hence the produced blazingly fast speeds. Hope this helps the community.

### Contributing
PLEASE, MAKE A PULL REQUEST SO WE CAN FINISH THIS PROJECT ASAP. Also, give it a star, for the sake of God.

### Author
**Brush Wayne aka MATBAN**


### License
Copyright © 2024, Brush Wayne
Released under the [MIT LICENSE](LICENSE).