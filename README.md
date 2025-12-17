## Flattening Combinations of Arrays and Records[^1]

Flattening is known to be a performance-boosting technique to orchestrate parallel computations on arbitrarily deeply nested arrays.
In this paper, we propose a flattening transformation that deals with nested data structures that are composed of combinations of arrays and records.
We choose the functional array programming language SaC as basis for this work, as it already supports flattening of homogeneously nested arrays, i.e. arrays in which all elements have the same shape.
We propose an extension of SaC's syntax for records that allows records and arrays to be used in homogeneously nested form, and provide an implementation of this record transformation in the SaC compiler.
Based on that extension, we show how any legal program that operates with such data structures can be transformed into an equivalent one that does not require any records at runtime.

```bibtex
@inproceedings{huijben2025flattening,
  author={Huijben, Reg
    and Aaldering, Jordy
    and Achten, Peter
    and Scholz, Sven-Bodo},
  title={Flattening Combinations of Arrays and Records},
  booktitle={Proceedings of the 25th International Symposium on Trends in Functional Programming},
  editor={Chang, Stephen and Hemann, Jason},
  publisher={Springer Nature},
  series={TFP '24},
  location={South Orange, NJ, USA},
  year=2025,
  month=jan,
  articleno=10,
  pages={220--240},
  numpages=21,
  isbn={978-3-031-74558-4},
  doi={10.1007/978-3-031-74558-4_10}
}
```

[^1]: https://doi.org/10.1007/978-3-031-74558-4_10
