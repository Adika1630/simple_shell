			--- SIMPLE SHELL PROJECT ---

This is a team project to build a simple UNIX command interpreter that provides 
a user interface to access and give orders to the operating system.

Project Files

File 			Description
----------------------------------------------------------------------------------
AUTHORS			File with names of the owners and authors of this project
README.md		Description of the project
_atoi.c			String functions
			* interactive
			* is_delim
			* _isalpha
			* _atoi
builtin.c		Builtin functions
			* _myexit
			* _mycd
			* _myhelp
builtin1.c		Alias functions
			* _myhistory
			* _myset_alias
			* set_alias
			* print_alias
			* _myalias
environ.c		Environment functions
			* _myenv
			* _getenv
			* _mysetenv
			* _myunsetenv
			* populate_env_list
errors.c		Functions to print error
			* _eputs
			* _eputchar
			* _putfd
			* _putsfd
errors1.c		Print error functions
			* _erratoi
			* print_error
			* print_d
			* convert_number
			* remove_comments
exits.c			String manipulation functions
			* _strncpy
			* _strncat
			* _strchr
getenv.c		Functions for environment variables
			* get_environ
			* _unsetenv
			* _setenv
getinfo.c		Functions for struct info_t
			* clear_info
			* set_info
			* free_info
getline.c		Functions for command line
	 		* input_buf
			* get_input
			* read_buf
			* _getline
			* sigintHandler
history.c		Manipulate history functions
			* get_history_file
			* write_history
			* read_history
			* build_history_list
			* renumber_history
lists.c			Linked lists functions
			* add_node
			* add_node_end
			* print_list_str
			* delete_node_at_index
			* free_list
lists1.c		More linked lists functions
			* list_len
			* list_to_strings
			* print_list
			* node_starts_with
			* get_node_index
main.c			Main function
			* main
memory.c		Free memory functions
			* bfree
parser.c		Path functions
			* is_cmd
			* dup_chars
			* find_path
realloc.c		Memory allocation functions
			* _memset
			* ffree
			* _realloc
shell_loop.c		Loop files
			* hsh
			* find_builtin
			* find_cmd
			* fork_cmd
shell.h			Header file
			* All includes
			* All prototypes
			* Definition of struct parameters
string.c		More string functions
			* _strlen
			* _strcmp
			* starts_with
			* _strcat
string1.c 		Even more string functions
			* _strcpy
			* _strdup
			* _puts
			* _putchar
tokenizer.c		Functions to tokenize path
			* strtow
			* strtow2
vars.c			Token manipulation functions
			* is_chain
			* check_chain
			* replace_alias
			* replace_vars
			* replace_string
