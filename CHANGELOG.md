CHANGELOG <br>
==============

## 6.3.7 (2019-02-18)
---------------------
- Fixed `include_unknown` in `lookup`
- Removed unused `initial_capacity` argument
- Improved `_get_str_hash` performance
- Implemented `save_pickle` and `load_pickle` to avoid having to create the
dictionary every time

## 6.3.6 (2019-02-11)
---------------------
- Added `create_dictionary()` feature

## 6.3.5 (2019-01-14)
---------------------
- Fixed `lookup_compound()` to return the correct `distance`

## 6.3.4 (2019-01-04)
---------------------
- Added `<self._replaced_words = dict()>` to track number of misspelled words
- Added `ignore_token` to `word_segmentation()` to ignore words with regular expression

## 6.3.3 (2018-12-05)
---------------------
- Added `word_segmentation()` feature

## 6.3.2 (2018-10-23)
---------------------
- Added `encoding` option to `load_dictionary()`

## 6.3.1 (2018-08-30)
---------------------
- Create a package for `symspellpy`

## 6.3.0 (2018-08-13)
---------------------
- Ported [SymSpell](https://github.com/wolfgarbe/SymSpell) v6.3