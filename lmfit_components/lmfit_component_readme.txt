[[Model]]
    (Model(one_pulse, prefix='one_') + Model(one_pulse, prefix='two_'))
[[Variables]]
    one_x_offset:      3.0740e-06 (init= 3.230253e-06)
    two_x_offset:      3.2960e-06 (init= 3.230253e-06)
    sum_amplitudes:    2.06743010 (init= 1.979657)
    diff_amplitudes:  -0.23544549 (init= 0)
    one_amplitude:     0.91599230  == '(sum_amplitudes+diff_amplitudes)/2'
    two_amplitude:     1.15143780  == '(sum_amplitudes-diff_amplitudes)/2'
