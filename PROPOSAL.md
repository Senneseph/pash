I would like a *nix-compatible shell similar to bash and Perl Shell (psh), which will be called "pash".

First we will decompose bash and figure out how it works so we can abstract it.
Our abstraction should allow us to rebuild the whole thing with a different brand (essentially forking the project).
We're doing this so that we have a reference program of the same name and to help make sure we fully understand its scope.
Then we will look at the ancient psh project, see what made it great, what modern equivalents there are, and then essentially make pash.
pash, ideally, is like a Perl-enhanced bash (haven't chosen version/dialect). Almost like a repl. But which excels at chaining functions and running commands.
And especially regex.

We want to modernize everything about pash eventually. For example, redesigning the interpreter in Rust, possibly limiting it.

"pash" is our "passion"! The Perl Again Shell