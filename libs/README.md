bash

```bash
cat * */* */*/* > README.md
```

vim

```
:g!/include/d
:g!/boost/d
:s/^\s*//
:%!uniq
```

bash, goto boost source dir

```bash
mkdir outputs
bcp \
    boost/algorithm/string/split.hpp \
    boost/algorithm/string/trim.hpp \
    boost/assert.hpp \
    boost/atomic.hpp \
    boost/atomic/capabilities.hpp \
    boost/atomic/detail/lockpool.hpp \
    boost/atomic/detail/operations_lockfree.hpp \
    boost/atomic/detail/pause.hpp \
    boost/config.hpp \
    boost/config/warning_disable.hpp \
    boost/cstdint.hpp \
    boost/date_time/posix_time/conversion.hpp \
    boost/detail/utf8_codecvt_facet.ipp \
    boost/detail/workaround.hpp \
    boost/filesystem/config.hpp \
    boost/filesystem/detail/utf8_codecvt_facet.hpp \
    boost/filesystem/operations.hpp \
    boost/filesystem/path.hpp \
    boost/filesystem/path_traits.hpp \
    boost/lexical_cast.hpp \
    boost/memory_order.hpp \
    boost/predef/platform.h \
    boost/scoped_array.hpp \
    boost/signals/connection.hpp \
    boost/signals/detail/named_slot_map.hpp \
    boost/signals/detail/signal_base.hpp \
    boost/signals/slot.hpp \
    boost/signals/trackable.hpp \
    boost/static_assert.hpp \
    boost/system/detail/error_code.ipp \
    boost/system/error_code.hpp \
    boost/system/system_error.hpp \
    boost/thread/condition_variable.hpp \
    boost/thread/csbl/memory/unique_ptr.hpp \
    boost/thread/detail/config.hpp \
    boost/thread/detail/tss_hooks.hpp \
    boost/thread/future.hpp \
    boost/thread/futures/future_error_code.hpp \
    boost/thread/locks.hpp \
    boost/thread/once.hpp \
    boost/thread/pthread/pthread_mutex_scoped_lock.hpp \
    boost/thread/thread_only.hpp \
    boost/thread/tss.hpp \
    boost/thread/xtime.hpp \
    boost/throw_exception.hpp \
    outputs
```
