# A Survey on Information Theoretic Bounds for the K-Means Algorithm

In this course project report, we survey some of the recent information theoretic bounds
derived for the famous Lloyd's Algorithm, commonly known as the k-means algorithm

## Abstract

Lloyd's algorithm [12], commonly known as the k-means algorithm, provides an intuitive
sub-optimal algorithmic solution to the data clustering problem. The k-means algorithm
has a number of variants and applications in different domains and is the most popular
clustering algorithm in Machine Learning. Despite its simplicity and popularity, there
is lack of information theoretic bounds on the clustering solutions. It is affected by
initialization strategies, along with the contuinity and unboundedness of the loss
function. In this survey, we peruse some recent strategies which try to find theoretic
bounds for the k-means solution based on assumptions on the underlying data distribution
or modified initialization strategies.

## References

1.  Ankit Aggarwal, Amit Deshpande, and Ravindran Kannan. Adaptive sampling for k-means
    clustering. In APPROX-RANDOM, pages 15–28, 01 2009. doi:
    10.1007/978-3-642-03685-9_2.

2.  Nir Ailon, Ragesh Jaiswal, and Claire Monteleoni. Streaming k-means approximation.
    In Y. Bengio, D. Schuurmans, J. D. Lafferty, C. K. I. Williams, and A. Culotta,
    editors, Advances in Neural Information Processing Systems 22, pages 10–18. Curran
    Associates, Inc., 2009. URL
    <http://papers.nips.cc/paper/3812-streaming-k-means-approximation.pdf>.

3.  David Arthur and Sergei Vassilvitskii. K-means++: The Advantages of Careful Seeding.
    In Proceedings of the Eighteenth Annual ACM-SIAM Symposium on Discrete Algorithms,
    SODA ’07, page 1027–1035, USA, 2007. Society for Industrial and Applied Mathematics.
    ISBN 9780898716245.

4.  Olivier Bachem, Mario Lucic, Hamed Hassani, and Andreas Krause. Fast and provably
    good seedings for k-means. In D. D. Lee, M. Sugiyama, U. V. Luxburg, I. Guyon, and
    R.  Garnett, editors, Advances in Neural Information Processing Systems 29, pages
    55–63.  Curran Associates, Inc., 2016. URL
    <http://papers.nips.cc/paper/6478-fast-and-provably-good-seedings-for-k-means.pdf>.

5.  Olivier Bachem, Mario Lucic, S. Hamed Hassani, and Andreas Krause. Approximate
    k-means++ in sublinear time. In AAAI, 2016.

6.  Olivier Bachem, Mario Lucic, and Andreas Krause. Distributed and provably good
    seedings for k-means in constant rounds. In Proceedings of the 34th International
    Conference on Machine Learning - Volume 70, ICML’17, page 292–300. JMLR.org, 2017.

7.  Bahman Bahmani, Benjamin Moseley, Andrea Vattani, Ravi Kumar, and Sergei
    Vassilvitskii. Scalable k-means++. Proc. VLDB Endow., 5(7):622–633, March 2012. ISSN
    2150-8097. doi: 10.14778/2180912.2180915. URL
    <https://doi.org/10.14778/2180912.2180915>.

8.  E. W. Forgy. Cluster analysis of multivariate data : efficiency versus
    interpretability of classifications. Biometrics, 21:768–769, 1965. URL
    <https://ci.nii.ac.jp/naid/10009668881/en/>.

9.  Teofilo F. Gonzalez. Clustering to minimize the maximum intercluster distance.
    Theoretical Computer Science, 38:293 – 306, 1985. ISSN 0304-3975. doi:
    https://doi.org/10.1016/0304-3975(85)90224-5. URL
    <http://www.sciencedirect.com/science/article/pii/0304397585902245>.

10. Leonard Kaufman and Peter Rousseeuw. Finding Groups in Data: An Introduction to
    Cluster Analysis. O'Reilly, 09 2009, ISBN 9780470317488

11. Leonid Kontorovich and Kavita Ramanan. Concentration Inequalities for Dependent
    Random Variables via the Martingale Method. The Annals of Probability, 2008.

12. S. Lloyd. Least Squares Quantization in PCM. IEEE Transactions on Information
    Theory, 1982.

13. K Marton. A Measure Concentration Inequality for Contracting Markov Chains.
    Geometric and Functional Analysis, 1996.

14. K Marton. K. Measure Concentration for a Class of Random Processes. Probability
    Theory and Related Fields, 1998.

15. Daniel Paulin. Concentration inequalities for markov chains by marton couplings and
    spectral methods. Electron. J. Probab., 20:32 pp., 2015. doi: 10.1214/EJP.v20-4039.
    <https://doi.org/10.1214/EJP.v20-4039>.

16. Paul-Marie Samson. Concentration of Measure Inequalities for Markov Chains and
    φ-Mixing Processes. The Annals of Probability, 2000.

17. Sami Sieranoja. How much k-means can be improved by using better initialization and
    repeats?  Pattern Recognition, 93, 04 2019. doi: 10.1016/j.patcog.2019.04.014.

18. Matus Telgarsky and Sanjoy Dasgupta. Moment-based uniform deviation bounds for
    $k$-means and friends. CoRR, abs/1311.1903, 2013. URL
    <http://arxiv.org/abs/1311.1903>.

19. Weizhong Zhao, Huifang Ma, and Qing He. Parallel k-means clustering based on
    mapreduce. In Martin Gilje Jaatun, Gansen Zhao, and Chunming Rong, editors, Cloud
    Computing, pages 674–679,
