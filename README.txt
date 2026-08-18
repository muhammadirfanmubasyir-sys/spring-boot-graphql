query  {
    findAll {
        id
        name
        team
    }
}

query  {
    findOne(id: "1") {
        id
        name
        team
    }
}

mutation  {
    create(name: "IRFAN", team: RCB) {
        id
        name
        team
    }
}

mutation  {
    update(id: "1", name: "MUBASYIR", team: CSK) {
        id
        name
        team
    }
}

mutation  {
    delete(id: "1") {
        id
        name
        team
    }
}
