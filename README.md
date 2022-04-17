function getAdmins(map) {
    let admins = [];
    for([key, value] of map) {
        if(value === 'Admin') {
            admins.push(key)
        }
    }
    return admins;
}

const usuarios = new map();

usuarios.set('Ronasses', 'Admin');
usuarios.set('Francieli');
usuarios.set('Arya', 'User');   
usuarios.set('Tefys', 'Admin');

console.log(getAdmins(usuarios));
