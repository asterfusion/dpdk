# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2019 Intel Corporation

allow_experimental_apis = true

sources = files('iavf_adminq.c', 'iavf_common.c', 'iavf_impl.c')

if cc.has_argument('-Wno-pointer-to-int-cast')
        cflags += '-Wno-pointer-to-int-cast'
endif
