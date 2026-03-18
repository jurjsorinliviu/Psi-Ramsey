# PSI-Ramsey Experiment Overview

## ablations
- Targets: 5
- Overall mean rank: structured_seed=2.229, teacher_mean_transfer=2.514, psi_ramsey_transfer=2.629
- structured_seed: mean_exact_r_clique_count=113631.4, mean_density_error=0.0025
- teacher_mean_transfer: mean_exact_r_clique_count=98941.2, mean_density_error=0.0260
- psi_ramsey_transfer: mean_exact_r_clique_count=96503.6, mean_density_error=0.0260

## interpretability
- Targets: 5
- Overall mean rank: portfolio_transfer=3.886, structure_oracle_transfer=4.100, exact_triangle_transfer=4.629
- portfolio_transfer: mean_exact_r_clique_count=2839.4, mean_density_error=0.0091
- structure_oracle_transfer: mean_exact_r_clique_count=8361.2, mean_density_error=0.0608
- exact_triangle_transfer: mean_exact_r_clique_count=6692.6, mean_density_error=0.0135

## matched_compute
- Targets: 5
- Overall mean rank: portfolio_transfer=3.471, exact_triangle_transfer=3.957, random_circulant=4.129
- portfolio_transfer: mean_exact_r_clique_count=2602.8, mean_density_error=0.0106
- exact_triangle_transfer: mean_exact_r_clique_count=6692.6, mean_density_error=0.0135
- random_circulant: mean_exact_r_clique_count=9724.2, mean_density_error=0.0048

## search
- Targets: 5
- Overall mean rank: portfolio_guided_search=2.538, structured_seed_local_search=2.625, random_local_search=2.650
- portfolio_guided_search: mean_search_best_score=2.4817, mean_validity_proxy=0.7000
- structured_seed_local_search: mean_search_best_score=2.4901, mean_validity_proxy=0.7000
- random_local_search: mean_search_best_score=2.1946, mean_validity_proxy=0.7000

## transfer
- Targets: 5
- Overall mean rank: portfolio_transfer=4.186, structure_oracle_transfer=4.500, random_circulant=4.514
- portfolio_transfer: mean_exact_r_clique_count=3834.2, mean_density_error=0.0075
- structure_oracle_transfer: mean_exact_r_clique_count=8361.2, mean_density_error=0.0608
- random_circulant: mean_exact_r_clique_count=9207.6, mean_density_error=0.0050
