add_library(
    functions
    chinese.cu
    divexact.cu
    modexp.cu
    modinv.cu
    multi_modexp.cu
    paillier_decrypt.cu
    paillier_encrypt.cu
    quorem_preinv.cu
    quorem.cu
    internal/modexp_impl.cu
)