include speedb/src.mk

rocksdb_lib_sources.txt: speedb/src.mk
	@echo -n "${LIB_SOURCES}" | tr ' ' '\n' > rocksdb_lib_sources.txt

gen_lib_sources: rocksdb_lib_sources.txt