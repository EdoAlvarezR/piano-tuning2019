# piano-tuning2019
Entropy-based, equal temperament tuning of piano, with recording and data processing in the Julia language.

The tuning process is based on the harmonization of overtones with inharmonicity coefficients implicitely calculated empirically. The equal-temperament deviation of higher and lower keys resembles the curve produced by expert aural tuning by minimizing the Shannon entropy produced by disonant overtones as explained in Hinrichsen 2012. Tuning candidates (local minima) are found through gradient-based non-linear optimization.

# References
* Hinrichsen, Haye. (2012). Entropy-based tuning of musical instruments. Revista Brasileira de Ensino de Física, 34(2), 1-8. https://dx.doi.org/10.1590/S1806-11172012000200004
* Joonas Tuovinen, Jamin Hu, Vesa Välimäki. (2019). Toward Automatic Tuning of the Piano. Proceedings of the 16th Sound & Music Computing Conference SMC 2019
