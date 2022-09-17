# Ascii Chord

A command line tool for showing how to play guitar chords

## Usage

```
$ aschord G               
This is how you play 'G' chord: 
    ◯ ◯ ◯  
┌─┬─┬─┬─┬─┐
│ │ │ │ │ │
├─┼─┼─┼─┼─┤
│ ◯ │ │ │ │
├─┼─┼─┼─┼─┤
◯ │ │ │ │ ◯
└─┴─┴─┴─┴─┘
```

## Installation

Install local version:

```
git clone git@github.com:yzhong52/ascii_chord.git
cd ascii_chord
cargo install --path .
```

Install from <https://crates.io/crates/chord>:

```
cargo install chord
```

## Development

```
cargo run -- G
```

## Release

```
cargo publish
```