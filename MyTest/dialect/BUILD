gentbl(
    name = "tensorflow_op_interfaces_inc_gen",
    compatible_with = get_compatible_with_cloud(),
    tbl_outs = [
        (
            "-gen-op-interface-decls",
            "ir/tf_op_interfaces.h.inc",
        ),
        (
            "-gen-op-interface-defs",
            "ir/tf_op_interfaces.cc.inc",
        ),
    ],
    tblgen = "@llvm-project//mlir:mlir-tblgen",
    td_file = "ir/tf_op_interfaces.td",
    td_srcs = [
        ":tensorflow_ops_td_files",
    ],
)
