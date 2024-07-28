将 ngx_core.h 中的如下数据结构用嵌套定义方式展示出来

```h
typedef struct ngx_module_s          ngx_module_t;
typedef struct ngx_conf_s            ngx_conf_t;
typedef struct ngx_cycle_s           ngx_cycle_t;
typedef struct ngx_pool_s            ngx_pool_t;
typedef struct ngx_chain_s           ngx_chain_t;
typedef struct ngx_log_s             ngx_log_t;
typedef struct ngx_open_file_s       ngx_open_file_t;
typedef struct ngx_command_s         ngx_command_t;
typedef struct ngx_file_s            ngx_file_t;
typedef struct ngx_event_s           ngx_event_t;
typedef struct ngx_event_aio_s       ngx_event_aio_t;
typedef struct ngx_connection_s      ngx_connection_t;
typedef struct ngx_thread_task_s     ngx_thread_task_t;
typedef struct ngx_ssl_s             ngx_ssl_t;
typedef struct ngx_proxy_protocol_s  ngx_proxy_protocol_t;
typedef struct ngx_quic_stream_s     ngx_quic_stream_t;
typedef struct ngx_ssl_connection_s  ngx_ssl_connection_t;
typedef struct ngx_udp_connection_s  ngx_udp_connection_t;

typedef void (*ngx_event_handler_pt)(ngx_event_t *ev);
typedef void (*ngx_connection_handler_pt)(ngx_connection_t *c);
```
