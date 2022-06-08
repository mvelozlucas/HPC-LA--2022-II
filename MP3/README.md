MINIPROYECTO 3

Implementación de Método Cadena Markov-Monte Carlo (MCMC)

1. Implementac MCMC con mejores práticas de Julia
  a) Matriz de probabilidad acumulada
  b) Cálculo de la matriz de probabilidad fuera del MCMC
  c)Variables globales p, Pi, T y f
  d)Agregar type annotations

2. Cálcular los tiempos de ejecucuión de entrada de 6x6

3. Aumentar el tamaño del Sistema de Ecuaiones Lineales Algebraico (SELA)
  a) 10x10, 30x30, 50x50
  b) Calcular tiempos

4. Implementar uso de AparseArrays.jl para optimizar memoria en SELA dispersos y calcular tiempos
  a) SELA  vs SELA dispersos
 
5. Probar alguna estrategía de Computo de Alto Rendimiento para disminuir el tiempo de ejecuón de MCMC
  Threads simplificados
    -Numba-python
    -Threads julia
 
6. Probar alguna propuesta de paralelización con cuda.c ó cuda.jl
